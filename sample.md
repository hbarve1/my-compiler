<!-- @format -->

#include<stdio.h>
#include<stdlib.h>
#include<conio.h>

struct stack
{
int data;
struct stact *next;
};
struct stack *pop(struct stack *top);
struct stack *push(struct stack \*top);

int main()
{
struct stack \*top;
int option,data;
//intialize stack
top=NULL;
do
{
printf("1. PUSH\n2. POP\n3. EXIT\n");
printf("\nSelect proper option:\n");
scanf("%d",&option);

        switch(option)
        {
            case 1 ://push
                    top = push(top);
                    break;
            case 2 ://pop
                    top = pop(top);
                    break;
            case 3 : exit(0);
        }
    }while(1);

}

struct stack *push(struct stack *top)
{
struct stack _c;
//creat new node
c=(struct stack_)malloc(sizeof(struct stack));

    if(c==NULL)
    {
        printf("Insufficient memory\n");
        return top;
    }
    printf("\nEnter data:\n");
    scanf("%d",&c->data);
    c->next=NULL;

    if(top==NULL)
        top=c;
    else
    {
        c->next=top;
        top=c;
    }
    return top;

}

struct stack *pop(struct stack *top)
{
struct stack \*c;
if(top==NULL)
{
printf("stack is empty\n");
return top;
}
printf("\nPoped data:%d",top->data);
c=top;
top=top->next;
free(c);
return top;
}

# <stdio.h>शामिल

# <stdlib.h>शामिल

# <conio.h>शामिल

संरचना ढेर
{
int डेटा;
संरचना ढेर *अगला;
};
संरचना ढेर *पॉप (struct ढेर शीर्ष *);
संरचना ढेर *धक्का (struct ढेर शीर्ष \*);

int मुख्य ()
{
संरचना ढेर \*शीर्ष;
int विकल्प, डेटा;
/ / ढेर intialize
शीर्ष = रिक्त;

    करना
    {
        लिख ("1 धक्का \ n2 पॉप \ n3 बाहर निकलें \ n. है.");
        लिख ("\ nSelect उचित विकल्प: \ n");
        पढ़("% d", &विकल्प);

        स्विच (विकल्प)
        {
            1 मामला: //धक्का
                    शीर्ष = धक्का (ऊपर);
                    तोड़;
           2  मामले:/ / पॉप
                    शीर्ष = पॉप (ऊपर);
                    तोड़;
            3 मामला: बाहर निकलें (0);
        }
    } जबकि (1);

}

संरचना ढेर * धक्का (संरचना ढेर *शीर्ष)
{
संरचना ढेर _ग;
/ / नए नोड बनाना
ग = (संरचना ढेर _) malloc ((संरचना ढेर) के आकार);

    अगर (ग == रिक्त)
    {
        लिख ("अपर्याप्त स्मृति \ n");
        शीर्ष वापस;
    }

    लिख ("\ दर्ज करें डेटा: \ n");
    पढ़("% d", &ग -> डेटा);
    ग ->अगला = बातिल;

    अगर (== Null)
        		शीर्ष = ग;
    अन्यथा
    {
        ग -> अगला = शीर्ष;
        शीर्ष = ग;
    }
    शीर्ष वापस;

}

संरचना ढेर _ पॉप (संरचना ढेर _ शीर्ष)
{
संरचना ढेर \* ग;
अगर (== Null)
{
लिख ("स्टैक खाली है \ n");
शीर्ष वापस;
}
लिख ("\ nPoped डेटा:% d", शीर्ष -> डेटा);
ग = शीर्ष;
शीर्ष = शीर्ष> अगला;
मुफ्त (ग);
शीर्ष वापस;
}

Simple for loop program in hindi

# <stdio.h> शामिल

int मुख्य ()
{
int i, j;

     (i = 0; i<10; i + +) केलिए

{
(j = 0; j <10; j + +) केलिए
लिख (" \* ");
}
0 वापसी;
}

# <stdio.h> शामिल

int मुख्य ()
{
int i, j;
i=0;
जब (i <10)
{
(j = 0; j <10; j + +) केलिए
लिख (" \* ");
i++;
}
0 वापसी;
}

# <stdio.h> शामिल

int मुख्य ()
{
int i, j;
i=0;
कर
{
(j = 0; j <10; j + +) केलिए
लिख (" \* ");
i++;
} जब (i <10);
0 वापसी;
}

# <stdio.h> शामिल

int मुख्य ()
{
int i, j;

     अगर (i <10)
           लिख("भारत");
    अन्यथा
           लिख("भारत");

0 वापसी;
}
