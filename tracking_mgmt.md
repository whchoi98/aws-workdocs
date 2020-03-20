---
description: 'Update : 2020-03-20'
---

# Appendix.추적과 관리

### 1.파일활동 추적

Amazon WorkDocs 활동 피드를 보고 파일 및 폴더에 대한 변경 사항을 추적하고 누가 변경했는지 확인합니다. 언제 파일을 보고 다운로드하고 주석을 달고 잠그고 삭제했는지 확인하고 특정 파일, 폴더 또는 사용자를 검색합니다. 활동 피드 검색은 활동 유형 및 수정한 날짜를 기준으로 필터링할 수 있습니다.

관리자 계정에서는 모든 로그를 추적하고 관리할 수 있습니다. 또한 사용자는 자신이 활동한 내역을 확인 할 수 있습니다.

![\[&#xADF8;&#xB9BC; 6.1 &#xD65C;&#xB3D9;&#xD53C;&#xB4DC; &#xAC80;&#xC0C9; &#xD654;&#xBA74;1\]](.gitbook/assets/6.1.activity_feed1.png)

관리자는 특정 문자열을 통해 원하는 활동피드를 검색할 수 있습니다.

![\[&#xADF8;&#xB9BC; 6.2 &#xD65C;&#xB3D9;&#xD53C;&#xB4DC; &#xAC80;&#xC0C9; &#xD654;&#xBA74; 2\]](.gitbook/assets/6.2.activity_feed2.png)

관리자는 다양한 태그 옵션을 통해 사용자별 추적이 가능합니다.

![\[&#xADF8;&#xB9BC; 6.3 &#xD65C;&#xB3D9;&#xD53C;&#xB4DC; &#xAC80;&#xC0C9; &#xD654;&#xBA74;3\]](.gitbook/assets/6.3.activity_feed3.png)

### 2. 관리

Amazon WorkDocs는 권한 사용을 통해 폴더 및 파일에 대한 액세스 권한을 제어합니다. 권한은 사용자 역할에 따라 적용됩니다.

### 역할

폴더 및 파일 권한은 둘 다 사용자 역할에 따라 부여됩니다. 다음은 폴더에 적용되는 Amazon WorkDocs에 정의된 역할입니다.

* 폴더 소유자 – 폴더 또는 파일의 소유자입니다.
* 폴더 공동 소유자 – 소유자가 폴더나 파일의 공동 소유자로 지정한 사용자 또는 그룹입니다.
* 폴더 기고자 – 폴더에 대한 액세스 제한 없이 폴더를 공유하는 사람입니다.
* 폴더 최종 사용자 – 폴더를 공유하지만 폴더에 대한 제한된 액세스 권한\(보기 전용\)을 가진 사람입니다.

다음 역할이 파일에 적용됩니다.

* 소유자 – 파일의 소유자입니다.
* 공동 소유자 – 소유자가 파일의 공동 소유자로 지정한 사용자 또는 그룹입니다.
* 기고자 – 파일에 대한 피드백을 요청 받은 사람입니다.
* 최종 사용자 – 파일을 공유하지만 파일에 대한 제한된 액세스 권한\(보기 전용\)을 가진 사람입니다.
* 익명 최종 사용자 – 외부 보기 링크를 통해 공유된 파일을 볼 수 있는 조직 외부의 미등록 사용자입니다. 별도로 지정된 경우가 아니면, 익명 최종 사용자에게는 최종 사용자와 동일한 권한이 부여됩니다.

### 공유 폴더 권한

다음은 공유 폴더에 대해 Amazon WorkDocs에서 정의하는 권한입니다.

* 보기 – 공유 폴더의 내용을 봅니다.
* 하위 폴더 보기 – 하위 폴더를 봅니다.
* 공유 보기 – 폴더를 공유하는 다른 사용자를 봅니다.
* 폴더 다운로드 – 폴더를 다운로드합니다.
* 하위 폴더 추가 – 하위 폴더를 추가합니다.
* 공유 – 다른 사용자와 최상위 폴더를 공유합니다.
* 공유 취소 – 최상위 폴더의 공유를 취소합니다.
* 하위 폴더 삭제 – 하위 폴더를 삭제합니다.
* 최상위 폴더 삭제 – 최상위 공유 폴더를 삭제합니다.

| 권한 | 폴더 소유 | 폴더 공동 소유 | 폴더 기고 | 폴더 최종 사용 |
| :--- | :--- | :--- | :--- | :--- |
| 보기 | O | O | O | O |
| 하위 폴더 보기 | O | O | O | O |
| 공유자 보기 | O | O | O | O |
| 다운로드 | O | O | O | O |
| 하위 폴더 추가 | O | O | O |  |
| 공유 | O | O |  |  |
| 공유 취소 | O | O |  |  |
| 하위 폴더 삭제 | O | O |  |  |
| 최상위 폴더 삭 | O |  |  |  |

### 파일 권한

다음은 공유 폴더에 없는 파일에 대해 Amazon WorkDocs에서 정의하는 권한입니다.

* 보기 – 파일을 봅니다.
* 삭제 – 파일을 삭제합니다.
* 주석 달기 – 파일에 피드백을 추가할 수 있습니다.
* 공유 보기 – 파일을 공유하는 다른 사용자를 봅니다.
* 주석 보기 – 다른 사용자의 피드백을 봅니다.
* 활동 보기 – 파일의 활동 기록을 봅니다.
* 버전 보기 – 파일의 이전 버전을 봅니다.
* 다운로드 – 파일을 다운로드합니다. 이는 기본 권한입니다. 공유 파일을 다운로드할 수 있는 기능을 파일 속성에서 허용하거나 거부할 수 있습니다.
* 다운로드 방지 – 파일을 다운로드할 수 없도록 합니다.
* 업로드 – 파일의 새 버전을 업로드합니다.
* 공유 – 파일을 다른 사용자와 공유합니다.
* 공유 취소 – 파일의 공유를 취소합니다.

| 권한 | 소유자/공동소유 | 기고 | 최종 사용 | 익명 최종 사용 |
| :--- | :--- | :--- | :--- | :--- |
| 보기 | O | O | O | O |
| 공유자 보기 | O | O | O | O |
| 다운로드 | O | O | O |  |
| 주석달기 | O | O |  |  |
| 주석보기 | O | O |  |  |
| 활동보기 | O | O |  |  |
| 버전보기 | O | O |  |  |
| 업로드 | O | O |  |  |
| 삭제 | O |  |  |  |
| 다운로드 방지 | O |  |  |  |
| 공유 | O |  |  |  |
| 공유취 | O |  |  |  |

### 공유 파일 권한

다음은 공유 폴더에 있는 파일에 대해 Amazon WorkDocs에서 정의하는 권한입니다.

* 보기 – 공유 폴더에 있는 파일을 봅니다.
* 공유 보기 – 파일을 공유하는 다른 사용자를 봅니다.
* 다운로드 – 파일을 다운로드합니다.
* 주석 달기 – 파일에 피드백을 추가할 수 있습니다.
* 주석 보기 – 다른 사용자의 피드백을 봅니다.
* 활동 보기 – 파일의 활동 기록을 봅니다.
* 버전 보기 – 파일의 이전 버전을 봅니다.
* 업로드 – 파일의 새 버전을 업로드합니다.
* 삭제 – 공유 폴더에 있는 파일을 삭제합니다.
* 다운로드 방지 – 파일을 다운로드할 수 없도록 합니다. 이 권한은 폴더에 있는 파일에 대한 기본 권한입니다.
* 공유 – 파일을 다른 사용자와 공유합니다.
* 공유 취소 – 파일의 공유를 취소합니다.
* 비공개 설명 – 소유자/공동 소유자는 자신의 설명에 대한 응답이 아니더라도 문서에 대한 모든 비공개 설명을 볼 수 있습니다.

<table>
  <thead>
    <tr>
      <th style="text-align:left">&#xAD8C;&#xD55C;</th>
      <th style="text-align:left">
        <p>&#xD3F4;&#xB354;&#xC18C;&#xC720;&#xC790;</p>
        <p>&#xACF5;&#xB3D9; &#xC18C;&#xC720;</p>
      </th>
      <th style="text-align:left">&#xD30C;&#xC77C; &#xC18C;&#xC720;</th>
      <th style="text-align:left">&#xD3F4;&#xB354; &#xAE30;&#xACE0;</th>
      <th style="text-align:left">&#xD3F4;&#xB354;
        <br />&#xCD5C;&#xC885; &#xC0AC;&#xC6A9;</th>
      <th style="text-align:left">
        <p>&#xC775;&#xBA85;</p>
        <p>&#xCD5C;&#xC885; &#xC0AC;&#xC6A9;</p>
      </th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">&#xBCF4;&#xAE30;</td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">O</td>
    </tr>
    <tr>
      <td style="text-align:left">&#xACF5;&#xC720;&#xC790; &#xBCF4;&#xAE30;</td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">O</td>
    </tr>
    <tr>
      <td style="text-align:left">&#xB2E4;&#xC6B4;&#xB85C;&#xB4DC;</td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">O</td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">&#xC8FC;&#xC11D;&#xB2EC;&#xAE30;</td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">O</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">&#xC8FC;&#xC11D;&#xBCF4;&#xAE30;</td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">O</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">&#xD65C;&#xB3D9;&#xBCF4;&#xAE30;</td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">O</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">&#xBC84;&#xC804;&#xBCF4;&#xAE30;</td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">O</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">&#xC5C5;&#xB85C;&#xB4DC;</td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">O</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">&#xC0AD;&#xC81C;</td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">O</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">&#xC774;&#xB984;&#xBC14;&#xAFB8;&#xAE30;</td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">O</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">&#xB2E4;&#xC6B4;&#xB85C;&#xB4DC;&#xBC29;&#xC9C0;</td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">O</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">&#xACF5;&#xC720;</td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">O</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">&#xACF5;&#xC720;&#xCDE8;</td>
      <td style="text-align:left">O</td>
      <td style="text-align:left">O</td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
      <td style="text-align:left"></td>
    </tr>
    <tr>
      <td style="text-align:left">&#xBAA8;&#xB4E0; &#xAC1C;&#xC778; &#xCF54;&#xBA58;&#xD2B8; &#xBCF4;</td>
      <td
      style="text-align:left">O</td>
        <td style="text-align:left">O</td>
        <td style="text-align:left"></td>
        <td style="text-align:left"></td>
        <td style="text-align:left"></td>
    </tr>
  </tbody>
</table>