# swkim
#include <stdio.h>

int main() {
    char name[50]; // 사용자 이름을 저장할 배열

    // 사용자로부터 이름 입력 받기
    printf("당신의 이름은 무엇인가요? ");
    scanf("%s", name);  // %s로 문자열 입력받기

    // 입력받은 이름으로 인사 메시지 출력
    printf("안녕하세요, %s님! 반갑습니다.\n", name);

    return 0;
}
