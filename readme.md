<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
<!-- saved from url=(0049)http://www.mathemainzel.info/files/x86asmref.html -->
<html><head><meta http-equiv="Content-Type" content="text/html; charset=windows-1252">
<link rel="stylesheet" href="./Intel 80x86 Assembly Language OpCodes_files/x86.css">

<meta name="Author" content="Walter H.">
<meta name="Generator" content="Microsoft Word 6.0 f. WinNT">

</head>
<body data-new-gr-c-s-check-loaded="14.1049.0" data-gr-ext-installed="">
  <h3>Mirror of: http://www.mathemainzel.info/files/x86asmref.html</h3>
<h2>Intel 80x86 Assembly Language OpCodes</h2>

<div>
The following table provides a list of x86-Assembler mnemonics, that is not complete. Most of them can be found, for others see at <a href="http://www.intel.com/" target="_blank">www.intel.com</a>
</div>

<ol>
<li value="0"><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#abrev">Notations and Format used in this Document</a></li>
<li value="1"><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#aaa">AAA</a> - Ascii Adjust for Addition</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#aad">AAD</a> - Ascii Adjust for Division</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#aam">AAM</a> - Ascii Adjust for Multiplication</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#aas">AAS</a> - Ascii Adjust for Subtraction</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#adc">ADC</a> - Add With Carry</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#add">ADD</a> - Arithmetic Addition</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#and">AND</a> - Logical And</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#arpl">ARPL</a> - Adjusted Requested Privilege Level of Selector</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#bound">BOUND</a> - Array Index Bound Check</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#bsf">BSF</a> - Bit Scan Forward</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#bsr">BSR</a> - Bit Scan Reverse</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#bswap">BSWAP</a> - Byte Swap </li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#bt">BT</a> - Bit Test </li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#btc">BTC</a> - Bit Test with Compliment  </li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#btr">BTR</a> - Bit Test with Reset  </li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#bts">BTS</a> - Bit Test and Set  </li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#call">CALL</a> - Procedure Call</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#cbw">CBW</a> - Convert Byte to Word</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#cdq">CDQ</a> - Convert Double to Quad</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#clc">CLC</a> - Clear Carry</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#cld">CLD</a> - Clear Direction Flag</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#cli">CLI</a> - Clear Interrupt Flag</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#clts">CLTS</a> - Clear Task Switched Flag</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#cmc">CMC</a> - Complement Carry Flag</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#cmp">CMP</a> - Compare</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#cmps">CMPS</a> - Compare String </li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#cmpxchg">CMPXCHG</a> - Compare and Exchange</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#cwd">CWD</a> - Convert Word to Doubleword</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#cwde">CWDE</a> - Convert Word to Extended Doubleword</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#daa">DAA</a> - Decimal Adjust for Addition</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#das">DAS</a> - Decimal Adjust for Subtraction</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#dec">DEC</a> - Decrement</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#div">DIV</a> - Divide</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#enter">ENTER</a> - Make Stack Frame</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#esc">ESC</a> - Escape</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#float">Floating point instuctions</a> - no descriptions</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#hlt">HLT</a> - Halt CPU</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#idiv">IDIV</a> - Signed Integer Division</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#imul">IMUL</a> - Signed Multiply</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#in">IN</a> - Input Byte or Word From Port</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#inc">INC</a> - Increment</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#ins">INS</a> - Input String from Port</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#int">INT</a> - Interrupt</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#into">INTO</a> - Interrupt on Overflow</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#invd">INVD</a> - Invalidate Cache  </li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#invlpg">INVLPG</a> - Invalidate Translation Look-Aside Buffer Entry</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#iret">IRET/IRETD</a> - Interrupt Return</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#ja">JA/JNBE</a> - Jump Above / Jump Not Below or Equal</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#jae">JAE/JNB</a> - Jump Above or Equal / Jump on Not Below</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#jb">JB/JNAE</a> - Jump Below / Jump Not Above or Equal</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#jbe">JBE/JNA</a> - Jump Below or Equal / Jump Not Above</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#jc">JC</a> - Jump on Carry</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#jcxz">JCXZ/JECXZ</a> - Jump if Register (E)CX is Zero</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#je">JE/JZ</a> - Jump Equal / Jump Zero</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#jg">JG/JNLE</a> - Jump Greater / Jump Not Less or Equal</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#jge">JGE/JNL</a> - Jump Greater or Equal / Jump Not Less</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#jl">JL/JNGE</a> - Jump Less / Jump Not Greater or Equal</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#jle">JLE/JNG</a> - Jump Less or Equal / Jump Not Greater</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#jmp">JMP</a> - Unconditional Jump</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#jnc">JNC</a> - Jump Not Carry</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#jne">JNE/JNZ</a> - Jump Not Equal / Jump Not Zero</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#jno">JNO</a> - Jump Not Overflow</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#jns">JNS</a> - Jump Not Signed</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#jnp">JNP/JPO</a> - Jump Not Parity / Jump Parity Odd</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#jo">JO</a> - Jump on Overflow</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#jp">JP/JPE</a> - Jump on Parity / Jump on Parity Even</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#js">JS</a> - Jump Signed</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#lahf">LAHF</a> - Load Register AH From Flags</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#lar">LAR</a> - Load Access Rights</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#lds">LDS</a> - Load Pointer Using DS</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#lea">LEA</a> - Load Effective Address</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#leave">LEAVE</a> - Restore Stack for Procedure Exit</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#les">LES</a> - Load Pointer Using ES</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#lfs">LFS</a> - Load Pointer Using FS</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#lgdt">LGDT</a> - Load Global Descriptor Table</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#lidt">LIDT</a> - Load Interrupt Descriptor Table </li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#lgs">LGS</a> - Load Pointer Using GS </li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#lldt">LLDT</a> - Load Local Descriptor Table</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#lmsw">LMSW</a> - Load Machine Status Word </li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#lock">LOCK</a> - Lock Bus</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#lods">LODS</a> - Load String</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#loop">LOOP</a> - Decrement CX and Loop if CX Not Zero</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#loope">LOOPE/LOOPZ</a> - Loop While Equal / Loop While Zero</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#loopnz">LOOPNZ/LOOPNE</a> - Loop While Not Zero / Loop While Not Equal</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#lsl">LSL</a> - Load Segment Limit </li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#lss">LSS</a> - Load Pointer Using SS</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#ltr">LTR</a> - Load Task Register  </li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#mov">MOV</a> - Move Byte or Word</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#movs">MOVS</a> - Move String </li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#movsx">MOVSX</a> - Move with Sign Extend </li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#movzx">MOVZX</a> - Move with Zero Extend</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#mul">MUL</a> - Unsigned Multiply</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#neg">NEG</a> - Two's Complement Negation</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#nop">NOP</a> - No Operation </li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#not">NOT</a> - One's Compliment Negation</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#or">OR</a> - Inclusive Logical OR</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#out">OUT</a> - Output Data to Port</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#outs">OUTS</a> - Output String to Port</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#pop">POP</a> - Pop Word off Stack</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#popa">POPA/POPAD</a> - Pop All Registers onto Stack</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#popf">POPF/POPFD</a> - Pop Flags off Stack</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#push">PUSH</a> - Push Word onto Stack</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#pusha">PUSHA/PUSHAD</a> - Push All Registers onto Stack</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#pushf">PUSHF/PUSHFD</a> - Push Flags onto Stack</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#rcl">RCL</a> - Rotate Through Carry Left</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#rcr">RCR</a> - Rotate Through Carry Right</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#rep">REP</a> - Repeat String Operation</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#repe">REPE/REPZ</a> - Repeat Equal / Repeat Zero</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#repne">REPNE/REPNZ</a> - Repeat Not Equal / Repeat Not Zero</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#ret">RET/RETF</a> - Return From Procedure</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#rol">ROL</a> - Rotate Left</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#ror">ROR</a> - Rotate Right</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#sahf">SAHF</a> - Store AH Register into FLAGS</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#sal">SAL/SHL</a> - Shift Arithmetic Left / Shift Logical Left</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#sar">SAR</a> - Shift Arithmetic Right</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#sbb">SBB</a> - Subtract with Borrow</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#scas">SCAS</a> - Scan String </li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#setae">SETAE/SETNB</a> - Set if Above or Equal / Set if Not Below</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#setb">SETB/SETNAE</a> - Set if Below / Set if Not Above or Equal</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#setbe">SETBE/SETNA</a> - Set if Below or Equal / Set if Not Above</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#sete">SETE/SETZ</a> - Set if Equal / Set if Zero</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#setne">SETNE/SETNZ</a> - Set if Not Equal / Set if Not Zero</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#setl">SETL/SETNGE</a> - Set if Less / Set if Not Greater or Equal</li> 
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#setge">SETGE/SETNL</a> - Set if Greater or Equal / Set if Not Less</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#setle">SETLE/SETNG</a> - Set if Less or Equal / Set if Not greater or Equal</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#setg">SETG/SETNLE</a> - Set if Greater / Set if Not Less or Equal</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#sets">SETS</a> - Set if Signed</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#setns">SETNS</a> - Set if Not Signed</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#setc">SETC</a> - Set if Carry</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#setnc">SETNC</a> - Set if Not Carry</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#seto">SETO</a> - Set if Overflow</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#setno">SETNO</a> - Set if Not Overflow</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#setp">SETP/SETPE</a> - Set if Parity / Set if Parity Even</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#setnp">SETNP/SETPO</a> - Set if No Parity / Set if Parity Odd</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#sgdt">SGDT</a> - Store Global Descriptor Table</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#sidt">SIDT</a> - Store Interrupt Descriptor Table</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#shr">SHR</a> - Shift Logical Right</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#shld">SHLD/SHRD</a> - Double Precision Shift</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#sldt">SLDT</a> - Store Local Descriptor Table</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#smsw">SMSW</a> - Store Machine Status Word</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#stc">STC</a> - Set Carry</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#std">STD</a> - Set Direction Flag</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#sti">STI</a> - Set Interrupt Flag</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#stos">STOS</a> - Store String </li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#str">STR</a> - Store Task Register</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#sub">SUB</a> - Subtract</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#test">TEST</a> - Test For Bit Pattern</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#verr">VERR</a> - Verify Read</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#verw">VERW</a> - Verify Write</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#wait">WAIT/FWAIT</a> - Event Wait</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#wbinvd">WBINVD</a> - Write-Back and Invalidate Cache</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#xchg">XCHG</a> - Exchange</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#xlat">XLAT/XLATB</a> - Translate</li>
<li><a href="https://github.com/mysterious4579/Intel-80x86-Assembly-Language-OpCodes/blob/main/readme.md#xor">XOR</a> - Exclusive OR</li>
</ol>

<h3><a name="abrev">Notations and Format used in this Document</a></h3>

<h4>Notation</h4>

<dl>
<dt>mnemonics</dt><dt></dt><dd>Instruction syntax</dd>
<dt>op</dt><dd>Instruction OpCode</dd>
<dt>xx</dt><dd>Additional Code bytes</dd>
<dt>s</dt><dd>Sign Bit<ul><li>E: Sign-extended 8-bit immediate data</li><li>N: Non</li></ul></dd>
<dt>w</dt><dd>Word/byte Bit<ul><li>W: 16-bit operanrs</li><li>B: 8-bit operanrs</li></ul></dd>
<dt>len</dt><dd>Instruction length</dd>
<dt>flags</dt><dd><ul><li><tt>--------c</tt> - Carry flag</li>
<li><tt>-------p-</tt> - Parity flag</li>
<li><tt>------a--</tt> - Auxiliary flag</li>
<li><tt>-----z---</tt> - Zero flag</li>
<li><tt>----s----</tt> - Sign flag</li>
<li><tt>---t-----</tt> - Trap flag</li>
<li><tt>--i------</tt> - Interrupt flag</li>
<li><tt>-d-------</tt> - Direction flag</li>
<li><tt>o--------</tt> - Overflow flag</li></ul></dd>
</dl>

<dl>
<dt><tt>mr</tt></dt><dd>Addressing mode Byte = MODRM(mod-reg-r/m)</dd>
<dt><tt>/0~7</tt></dt><dd>2nd or 3rd Opcode (MODRM bits 5,4,3 from reg field)</dd>
<dt><tt>d0 d1</tt></dt><dd>Displacement [Low-byte High-byte]</dd>
<dt><tt>i0 i1</tt></dt><dd>Immediate word value</dd>
<dt><tt>o0 o1</tt></dt><dd>Offset value</dd>
<dt><tt>s0 s1</tt></dt><dd>Segment value</dd>
</dl>

<dl>
<dt><tt>r0</tt></dt><dd>Relative Short Displacement to label 'sl' (-128/+127 bytes)</dd>
<dt><tt>r0 r1</tt></dt><dd>Relative Long  Displacement to label 'll' (-32768/+32767 bytes)</dd>
</dl>

<h4>Mnemonic Notation</h4>

<table border="0" cellpadding="4" cellspacing="0">
<tbody>
<tr valign="top">
<td>
<dl>
<dt><tt>mb</tt></dt><dd>memory byte</dd>
<dt><tt>mw</tt></dt><dd>memory word</dd>
<dt><tt>md</tt></dt><dd>memory double word</dd>
<dt><tt>mq</tt></dt><dd>memory quad word</dd>
</dl>
</td>
<td>
<dl>
<dt><tt>rb</tt></dt><dd>register byte</dd>
<dt><tt>rw</tt></dt><dd>register word</dd>
<dt><tt>rd</tt></dt><dd>register double word</dd>
</dl>
</td>
<td>
<dl>
<dt><tt>rmb</tt></dt><dd>register or memory byte</dd>
<dt><tt>rmw</tt></dt><dd>register or memory word</dd>
</dl>
</td>
</tr>
<tr valign="top">
<td>
<dl>
<dt><tt>sl</tt></dt><dd>short label</dd>
<dt><tt>ll</tt></dt><dd>long label</dd>
</dl>
<dl>
<dt><tt>np</tt></dt><dd>near pointer</dd>
<dt><tt>fp</tt></dt><dd>far pointer</dd>
</dl>
</td>
<td>
<dl>
<dt><tt>ib</tt></dt><dd>immediate byte</dd>
<dt><tt>iw</tt></dt><dd>immediate word</dd>
</dl>
</td>
<td>
<dl>
<dt><tt>mwr</tt></dt><dd>memory word real</dd>
<dt><tt>mdr</tt></dt><dd>memory double word real</dd>
<dt><tt>mqr</tt></dt><dd>memory quad word real</dd>
<dt><tt>mtr</tt></dt><dd>memory ten byte real</dd>
</dl>
</td>
</tr>
<tr valign="top">
<td>
<dl>
<dt><tt>cr</tt></dt><dd>control register</dd>
</dl>
</td>
<td>
<dl>
<dt><tt>dr</tt></dt><dd>debug register</dd>
</dl>
</td>
<td>
<dl>
<dt><tt>tr</tt></dt><dd>test register</dd>
</dl>
</td>
</tr>
<tr>
<td align="center" colspan="3">

<table border="1" cellpadding="2" cellspacing="0">
<caption>Instruction General Format</caption>
<colgroup>
<col width="20%">
<col width="20%">
<col width="20%">
<col width="20%">
<col width="20%">
</colgroup>
<tbody>
<tr>
<td>PreFix</td>
<td>OpCode</td>
<td>modRM</td>
<td>Disp</td>
<td>Imm</td>
</tr>
</tbody>
</table>

</td>
</tr>
</tbody>
</table>

<hr>

<h4><a name="aaa">AAA - Ascii Adjust for Addition</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>AAA</tt></td><td><tt>37</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>------a-</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>AAA</tt></dd>
<dt>Modifies flags</dt><dd>AF CF (OF,PF,SF,ZF undefined)</dd>
</dl>
<p>
Changes contents of AL to valid unpacked decimal.<br>
The high order nibble is zeroed.
</p></div>

<h4><a name="aad">AAD - Ascii Adjust for Division</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>AAD</tt></td><td><tt>D5 0A</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>----sz-p</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>AAD</tt></dd>
<dt>Modifies flags</dt><dd>SF ZF PF (AF,CF,OF undefined)</dd>
</dl>
<p>
Used before dividing unpacked decimal numbers.<br>
Multiplies AH by 10 and the adds result into AL.  Sets AH to zero.<br>
This instruction is also known to have an undocumented behavior.
</p></div>

<h4><a name="aam">AAM - Ascii Adjust for Multiplication</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>AAM</tt></td><td><tt>D4 0A</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>----sz-p</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>AAM</tt></dd>
<dt>Modifies flags</dt><dd>PF SF ZF (AF,CF,OF undefined)</dd>
</dl>
<p>
Used after multiplication of two unpacked decimal numbers, this<br>
instruction adjusts an unpacked decimal number.  The high order<br>
nibble of each byte must be zeroed before using this instruction.<br>
This instruction is also known to have an undocumented behavior.
</p></div>

<h4><a name="aas">AAS - Ascii Adjust for Subtraction</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>AAS</tt></td><td><tt>3F</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>------a-</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>AAS</tt></dd>
<dt>Modifies flags</dt><dd>AF CF (OF,PF,SF,ZF undefined)</dd>
</dl>
<p>
Corrects result of a previous unpacked decimal subtraction in AL.<br>
High order nibble is zeroed.<br>
</p></div>

<h4><a name="adc">ADC - Add With Carry</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>ADC&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;AL,ib</tt></td><td><tt>14 i0</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>ADC&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;AX,iw</tt></td><td><tt>15 i0 i1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>3</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>ADC&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rb,rmb</tt></td><td><tt>12 mr d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2~4</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>ADC&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rw,rmw</tt></td><td><tt>13 mr d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>ADC&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb,ib</tt></td><td><tt>80 /2 d0 d1 i0</tt></td><td><tt>NB</tt></td><td><tt>3~5</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>ADC&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,iw</tt></td><td><tt>81 /2 d0 d1 i0 i1</tt></td><td><tt>NW</tt></td><td><tt>4~6</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>ADC&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,ib</tt></td><td><tt>83 /2 d0 d1 i0</tt></td><td><tt>EW</tt></td><td><tt>3~5</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>ADC&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb,rb</tt></td><td><tt>10 mr d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2~4</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>ADC&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,rw</tt></td><td><tt>11 mr d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>o---szap</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>ADC&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dest,src</tt></dd>
<dt>Modifies flags</dt><dd>AF CF OF SF PF ZF</dd>
</dl>
<p>
Sums two binary operands placing the result in the destination.<br>
If CF is set, a 1 is added to the destination.
<br>
</p></div>

<h4><a name="add">ADD - Arithmetic Addition</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>ADD&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;AL,ib</tt></td><td><tt>04 i0</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>ADD&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;AX,iw</tt></td><td><tt>05 i0 i1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>3</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>ADD&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rb,rmb</tt></td><td><tt>02 mr d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2~4</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>ADD&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rw,rmw</tt></td><td><tt>03 mr d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>ADD&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb,ib</tt></td><td><tt>80 /0 d0 d1 i0</tt></td><td><tt>NB</tt></td><td><tt>3~5</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>ADD&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,iw</tt></td><td><tt>81 /0 d0 d1 i0 i1</tt></td><td><tt>NW</tt></td><td><tt>4~6</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>ADD&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,ib</tt></td><td><tt>83 /0 d0 d1 i0</tt></td><td><tt>EW</tt></td><td><tt>3~5</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>ADD&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb,rb</tt></td><td><tt>00 mr d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2~4</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>ADD&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,rw</tt></td><td><tt>01 mr d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>o---szap</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>ADD&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dest,src</tt></dd>
<dt>Modifies flags</dt><dd>AF CF OF PF SF ZF</dd>
</dl>
<p>
Adds "src" to "dest" and replacing the original contents of "dest".<br>
Both operands are binary.
<br>
</p></div>

<h4><a name="and">AND - Logical And</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>AND&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;AL,ib</tt></td><td><tt>24 i0</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2</tt></td><td><tt>0---sz-p</tt></td></tr>
<tr><td><tt>AND&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;AX,iw</tt></td><td><tt>25 i0 i1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>3</tt></td><td><tt>0---sz-p</tt></td></tr>
<tr><td><tt>AND&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rb,rmb</tt></td><td><tt>22 mr d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2~4</tt></td><td><tt>0---sz-p</tt></td></tr>
<tr><td><tt>AND&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rw,rmw</tt></td><td><tt>23 mr d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>0---sz-p</tt></td></tr>
<tr><td><tt>AND&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb,ib</tt></td><td><tt>80 /4 d0 d1 i0</tt></td><td><tt>NB</tt></td><td><tt>3~5</tt></td><td><tt>0---sz-p</tt></td></tr>
<tr><td><tt>AND&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,iw</tt></td><td><tt>81 /4 d0 d1 i0 i1</tt></td><td><tt>NW</tt></td><td><tt>4~6</tt></td><td><tt>0---sz-p</tt></td></tr>
<tr><td><tt>AND&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,ib</tt></td><td><tt>83 /4 d0 d1 i0</tt></td><td><tt>EW</tt></td><td><tt>3~5</tt></td><td><tt>0---sz-p</tt></td></tr>
<tr><td><tt>AND&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb,rb</tt></td><td><tt>20 mr d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2~4</tt></td><td><tt>0---sz-p</tt></td></tr>
<tr><td><tt>AND&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,rw</tt></td><td><tt>21 mr d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>0---sz-p</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>AND&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dest,src</tt></dd>
<dt>Modifies flags</dt><dd>CF OF PF SF ZF (AF undefined)</dd>
</dl>
<p>
Performs a logical AND of the two operands replacing the destination with the result.
</p></div>

<h4><a name="arpl">ARPL - Adjusted Requested Privilege Level of Selector  (286+ protected mode)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>ARPL&nbsp;&nbsp;&nbsp;&nbsp;rmw,rw&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[286]</tt></td><td><tt>63 mr d0 d1</tt></td><td>&nbsp;</td><td><tt>2~4</tt></td><td><tt>-----z--</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>ARPL&nbsp;&nbsp;&nbsp;&nbsp;dest,src</tt></dd>
<dt>Modifies flags</dt><dd>ZF</dd>
</dl>
<p>
Compares the RPL bits of "dest" against "src".  If the RPL bits<br>
of "dest" are less than "src", the destination RPL bits are set<br>
equal to the source RPL bits and the Zero Flag is set.  Otherwise<br>
the Zero Flag is cleared.
</p></div>

<h4><a name="bound">BOUND - Array Index Bound Check (80188+)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>BOUND&nbsp;&nbsp;&nbsp;rw,rmw&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[186]</tt></td><td><tt>62 mr d0 d1</tt></td><td>&nbsp;</td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>BOUND&nbsp;&nbsp;&nbsp;src,limit</tt></dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Array index in source register is checked against upper and lower<br>
bounds in memory source.  The first word located at "limit" is<br>
the lower boundary and the word at "limit+2" is the upper array bound.<br>
Interrupt 5 occurs if the source value is less than or higher than<br>
the source.
</p></div>

<h4><a name="bsf">BSF - Bit Scan Forward  (386+ only)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>BSF&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rw,rmw&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F BC mr d0 d1</tt></td><td>&nbsp;</td><td><tt>3~5</tt></td><td><tt>-----z--</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>BSF&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dest,src</tt></dd>
<dt>Modifies flags</dt><dd>ZF</dd>
</dl>
<p>
Scans source operand for first bit set.  Sets ZF if a bit is found<br>
set and loads the destination with an index to first set bit.  Clears<br>
ZF is no bits are found set.  BSF scans forward across bit pattern<br>
(0-n) while BSR scans in reverse (n-0).
</p></div>

<h4><a name="bsr">BSR - Bit Scan Reverse  (386+ only)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>BSR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rw,rmw&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F BD mr d0 d1</tt></td><td>&nbsp;</td><td><tt>3~5</tt></td><td><tt>-----z--</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>BSR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dest,src</tt></dd>
<dt>Modifies flags</dt><dd>ZF</dd>
</dl>
<p>
Scans source operand for first bit set.  Sets ZF if a bit is found<br>
set and loads the destination with an index to first set bit.  Clears<br>
ZF is no bits are found set.  BSF scans forward across bit pattern<br>
(0-n) while BSR scans in reverse (n-0).
</p></div>

<h4><a name="bswap">BSWAP - Byte Swap  (486+ only)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>BSWAP&nbsp;&nbsp;&nbsp;eax&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[486]</tt></td><td><tt>0F C8</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>BSWAP&nbsp;&nbsp;&nbsp;ecx&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[486]</tt></td><td><tt>0F C9</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>BSWAP&nbsp;&nbsp;&nbsp;edx&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[486]</tt></td><td><tt>0F CA</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>BSWAP&nbsp;&nbsp;&nbsp;ebx&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[486]</tt></td><td><tt>0F CB</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>BSWAP&nbsp;&nbsp;&nbsp;esp&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[486]</tt></td><td><tt>0F CC</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>BSWAP&nbsp;&nbsp;&nbsp;ebp&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[486]</tt></td><td><tt>0F CD</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>BSWAP&nbsp;&nbsp;&nbsp;esi&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[486]</tt></td><td><tt>0F CE</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>BSWAP&nbsp;&nbsp;&nbsp;edi&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[486]</tt></td><td><tt>0F CF</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>BSWAP&nbsp;&nbsp;&nbsp;reg32</tt></dd>
<dt>Modifies flags</dt><dd>none</dd>
</dl>
<p>
Changes the byte order of a 32 bit register from big endian to<br>
little endian or vice versa.   Result left in destination register<br>
is undefined if the operand is a 16 bit register.
</p></div>

<h4><a name="bt">BT - Bit Test  (386+ only)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>BT&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,ib&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F BA /4 d0 d1 i0</tt></td><td>&nbsp;</td><td><tt>4~6</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>BT&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,rw&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F A3 mr d0 d1</tt></td><td>&nbsp;</td><td><tt>3~5</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>BT&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dest,src</tt></dd>
<dt>Modifies flags</dt><dd>CF</dd>
</dl>
<p>
The destination bit indexed by the source value is copied into the Carry Flag.
</p></div>

<h4><a name="btc">BTC - Bit Test with Compliment  (386+ only)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>BTC&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,ib&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F BA /7 d0 d1 i0</tt></td><td>&nbsp;</td><td><tt>4~6</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>BTC&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,rw&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F BB mr d0 d1</tt></td><td>&nbsp;</td><td><tt>3~5</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>BTC&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dest,src</tt></dd>
<dt>Modifies flags</dt><dd>CF</dd>
</dl>
<p>
The destination bit indexed by the source value is copied into the<br>
Carry Flag after being complimented (inverted).
</p></div>

<h4><a name="btr">BTR - Bit Test with Reset  (386+ only)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>BTR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,ib&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F BA /6 d0 d1 i0</tt></td><td>&nbsp;</td><td><tt>4~6</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>BTR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,rw&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F B3 mr d0 d1</tt></td><td>&nbsp;</td><td><tt>3~5</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>BTR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dest,src</tt></dd>
<dt>Modifies flags</dt><dd>CF</dd>
</dl>
<p>
The destination bit indexed by the source value is copied into the<br>
Carry Flag and then cleared in the destination.
</p></div>

<h4><a name="bts">BTS - Bit Test and Set  (386+ only)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>BTS&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,ib&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F BA /5 d0 d1 i0</tt></td><td>&nbsp;</td><td><tt>4~6</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>BTS&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,rw&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F AB mr d0 d1</tt></td><td>&nbsp;</td><td><tt>3~5</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>BTS&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dest,src</tt></dd>
<dt>Modifies flags</dt><dd>CF</dd>
</dl>
<p>
The destination bit indexed by the source value is copied into the<br>
Carry Flag and then set in the destination.
</p></div>

<h4><a name="call">CALL - Procedure Call</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>CALL&nbsp;&nbsp;&nbsp;&nbsp;np</tt></td><td><tt>E8 o0 o1</tt></td><td>&nbsp;</td><td><tt>3</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>CALL&nbsp;&nbsp;&nbsp;&nbsp;rw</tt></td><td><tt>FF /2 d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>CALL&nbsp;&nbsp;&nbsp;&nbsp;DWORD&nbsp;PTR[rw]</tt></td><td><tt>FF /3 d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>CALL&nbsp;&nbsp;&nbsp;&nbsp;FAR&nbsp;PTR&nbsp;fp</tt></td><td><tt>9A o0 o1 sl sh</tt></td><td>&nbsp;</td><td><tt>5</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>CALL&nbsp;&nbsp;&nbsp;&nbsp;destination</tt></dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Pushes Instruction Pointer (and Code Segment for far calls) onto<br>
stack and loads Instruction Pointer with the address of proc-name.<br>
Code continues with execution at CS:IP.
</p></div>

<h4><a name="cbw">CBW - Convert Byte to Word</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>CBW</tt></td><td><tt>98</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>CBW</tt></dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Converts byte in AL to word Value in AX by extending sign of AL throughout register AH.
</p></div>

<h4><a name="cdq">CDQ - Convert Double to Quad  (386+ only)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>CDQ&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[32bit]</tt></td><td><tt>66| 99</tt></td><td>&nbsp;</td><td><tt>1+1</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>CDQ</tt></dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Converts signed DWORD in EAX to a signed quad word in EDX:EAX by<br>
extending the high order bit of EAX throughout EDX
</p></div>

<h4><a name="clc">CLC - Clear Carry</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>CLC</tt></td><td><tt>F8</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>CLC</tt></dd>
<dt>Modifies flags</dt><dd>CF</dd>
</dl>
<p>
Clears the Carry Flag.
</p></div>

<h4><a name="cld">CLD - Clear Direction Flag</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>CLD</tt></td><td><tt>FC</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>-0------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>CLD</tt></dd>
<dt>Modifies flags</dt><dd>DF</dd>
</dl>
<p>
Clears the Direction Flag causing string instructions to increment the SI and DI index registers.
</p></div>

<h4><a name="cli">CLI - Clear Interrupt Flag (Disable Interrupts)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>CLI</tt></td><td><tt>FA</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--0-----</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>CLI</tt></dd>
<dt>Modifies flags</dt><dd>IF</dd>
</dl>
<p>
Disables the maskable hardware interrupts by clearing the Interrupt<br>
flag.  NMI's and software interrupts are not inhibited.
</p></div>

<h4><a name="clts">CLTS - Clear Task Switched Flag  (286+ privileged)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>CLTS&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[286]</tt></td><td><tt>0F 06</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>CLTS</tt></dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Clears the Task Switched Flag in the Machine Status Register.  This<br>
is a privileged operation and is generally used only by operating system code.
</p></div>

<h4><a name="cmc">CMC - Complement Carry Flag</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>CMC</tt></td><td><tt>F5</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>CMC</tt></dd>
<dt>Modifies flags</dt><dd>CF</dd>
</dl>
<p>
Toggles (inverts) the Carry Flag
</p></div>

<h4><a name="cmp">CMP - Compare</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>CMP&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;AL,ib</tt></td><td><tt>3C i0</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>CMP&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;AX,iw</tt></td><td><tt>3D i0 i1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>3</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>CMP&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rb,rmb</tt></td><td><tt>3A mr d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2~4</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>CMP&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rw,rmw</tt></td><td><tt>3B mr d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>CMP&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb,ib</tt></td><td><tt>80 /7 d0 d1 i0</tt></td><td><tt>NB</tt></td><td><tt>3~5</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>CMP&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,iw</tt></td><td><tt>81 /7 d0 d1 i0 i1</tt></td><td><tt>NW</tt></td><td><tt>4~6</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>CMP&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,ib</tt></td><td><tt>83 /7 d0 d1 i0</tt></td><td><tt>EW</tt></td><td><tt>3~5</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>CMP&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb,rb</tt></td><td><tt>38 mr d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2~4</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>CMP&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,rw</tt></td><td><tt>39 mr d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>o---szap</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>CMP&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dest,src</tt></dd>
<dt>Modifies flags</dt><dd>AF CF OF PF SF ZF</dd>
</dl>
<p>
Subtracts source from destination and updates the flags but does<br>
not save result.  Flags can subsequently be checked for conditions.
</p></div>

<h4><a name="cmps">CMPS - Compare String (Byte, Word or Doubleword)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>CMPSB</tt></td><td><tt>A6</tt></td><td><tt>&nbsp;B</tt></td><td><tt>1</tt></td><td><tt>od--szap</tt></td></tr>
<tr><td><tt>CMPSW</tt></td><td><tt>A7</tt></td><td><tt>&nbsp;W</tt></td><td><tt>1</tt></td><td><tt>od--szap</tt></td></tr>
<tr><td><tt>CMPSD&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[32bit]</tt></td><td><tt>66| A7</tt></td><td><tt>&nbsp;D</tt></td><td><tt>1+1</tt></td><td><tt>od--szap</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>CMPS&nbsp;&nbsp;&nbsp;&nbsp;dest,src</tt><br>
<tt>CMPSB</tt>
<br>
<tt>CMPSW</tt>
<br>
<tt>CMPSD&nbsp;&nbsp;&nbsp;(386+&nbsp;only)</tt>
</dd>
<dt>Modifies flags</dt><dd>AF CF OF PF SF ZF</dd>
</dl>
<p>
Subtracts destination value from source without saving results.<br>
Updates flags based on the subtraction and  the index registers<br>
(E)SI and (E)DI are incremented or decremented depending on the<br>
state of the Direction Flag.  CMPSB inc/decrements the index<br>
registers by 1, CMPSW inc/decrements by 2, while CMPSD increments<br>
or decrements by 4.  The REP prefixes can be used to process<br>
entire data items.
</p></div>

<h4><a name="cmpxchg">CMPXCHG/CMPXCHG8B - Compare and Exchange</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>CMPXCHG&nbsp;rmb,rb&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[486]</tt></td><td><tt>0F A6 mr d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>3~5</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>CMPXCHG&nbsp;rmw,rw&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[486]</tt></td><td><tt>0F A7 mr d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>3~5</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>CMPXCHG&nbsp;rmb,rb&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[486]</tt></td><td><tt>0F B0 mr d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>3~5</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>CMPXCHG&nbsp;rmw,rw&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[486]</tt></td><td><tt>0F B1 mr d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>3~5</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>CMPXCHG8B&nbsp;rmq,rd&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[P5]</tt></td><td><tt>0F C7 mr d0 d1</tt></td><td>&nbsp;</td><td><tt>3~5</tt></td><td><tt>-----z--</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>CMPXCHG&nbsp;dest,src&nbsp;&nbsp;(486+)</tt><br>
<tt>CMPXCHG8B&nbsp;dest,&nbsp;src&nbsp;(P5+)</tt>
</dd>
<dt>Modifies flags</dt><dd>AF CF OF PF SF ZF</dd>
</dl>
<p>
Compares the accumulator (8-32 bits) with "dest".  If equal the<br>
"dest" is loaded with "src", otherwise the accumulator is loaded<br>
with "dest".
</p></div>

<h4><a name="cwd">CWD - Convert Word to Doubleword</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>CWD</tt></td><td><tt>99</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>CWD</tt></dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Extends sign of word in register AX throughout register DX forming<br>
a doubleword quantity in DX:AX.
</p></div>

<h4><a name="cwde">CWDE - Convert Word to Extended Doubleword  (386+ only)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>CWDE&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[32bit]</tt></td><td><tt>66| 98</tt></td><td>&nbsp;</td><td><tt>1+1</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>CWDE</tt></dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Converts a signed word in AX to a signed doubleword in EAX by<br>
extending the sign bit of AX throughout EAX.
</p></div>

<h4><a name="daa">DAA - Decimal Adjust for Addition</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>DAA</tt></td><td><tt>27</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>----szap</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>DAA</tt></dd>
<dt>Modifies flags</dt><dd>AF CF PF SF ZF (OF undefined)</dd>
</dl>
<p>
Corrects result (in AL) of a previous BCD addition operation.<br>
Contents of AL are changed to a pair of packed decimal digits.
</p></div>

<h4><a name="das">DAS - Decimal Adjust for Subtraction</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>DAS</tt></td><td><tt>2F</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>----szap</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>DAS</tt></dd>
<dt>Modifies flags</dt><dd>AF CF PF SF ZF (OF undefined)</dd>
</dl>
<p>
Corrects result (in AL) of a previous BCD subtraction operation.<br>
Contents of AL are changed to a pair of packed decimal digits.
</p></div>

<h4><a name="dec">DEC - Decrement</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>DEC&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;AX</tt></td><td><tt>48</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>DEC&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;BP</tt></td><td><tt>4C</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>DEC&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;BX</tt></td><td><tt>4A</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>DEC&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;CX</tt></td><td><tt>49</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>DEC&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DI</tt></td><td><tt>4F</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>DEC&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DX</tt></td><td><tt>49</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>DEC&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb</tt></td><td><tt>FE /1 d0 d1</tt></td><td>&nbsp;</td><td><tt>2~4</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>DEC&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw</tt></td><td><tt>FF /1 d0 d1</tt></td><td>&nbsp;</td><td><tt>2~4</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>DEC&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;SI</tt></td><td><tt>4D</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>DEC&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;SP</tt></td><td><tt>4B</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>o---szap</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>DEC&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dest</tt></dd>
<dt>Modifies flags</dt><dd>AF OF PF SF ZF</dd>
</dl>
<p>
Unsigned binary subtraction of one from the destination.
</p></div>

<h4><a name="div">DIV - Divide</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>DIV&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb</tt></td><td><tt>F6 /6 d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2~4</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>DIV&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw</tt></td><td><tt>F7 /6 d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>o---szap</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>DIV&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;src</tt></dd>
<dt>Modifies flags</dt><dd>(AF,CF,OF,PF,SF,ZF undefined)</dd>
</dl>
<p>
Unsigned binary division of accumulator by source.  If the source<br>
divisor is a byte value then AX is divided by "src" and the quotient<br>
is placed in AL and the remainder in AH.  If source operand is a word<br>
value, then DX:AX is divided by "src" and the quotient is stored in AX<br>
and the remainder in DX.
</p></div>

<h4><a name="enter">ENTER - Make Stack Frame  (80188+)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>ENTER&nbsp;&nbsp;&nbsp;iw,ib&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[186]</tt></td><td><tt>C8 i0 i1 i0</tt></td><td>&nbsp;</td><td><tt>4</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>ENTER&nbsp;&nbsp;&nbsp;locals,level</tt></dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Modifies stack for entry to procedure for high level language.<br>
Operand "locals" specifies the amount of storage to be allocated<br>
on the stack.   "Level" specifies the nesting level of the routine.<br>
Paired with the LEAVE instruction, this is an efficient method of<br>
entry and exit to procedures.
</p></div>

<h4><a name="float">A description of the floating point instructions is not available at yet.</a></h4>
The following table has been provided for op-codes:<br>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>F2XM1</tt></td><td><tt>D9 F0</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FABS</tt></td><td><tt>D9 E1</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FADD</tt></td><td><tt>DE C1</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FADD&nbsp;&nbsp;&nbsp;&nbsp;mdr</tt></td><td><tt>D8 /0 d0 d1</tt></td><td><tt>&nbsp;D</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FADD&nbsp;&nbsp;&nbsp;&nbsp;mqr</tt></td><td><tt>DC /0 d0 d1</tt></td><td><tt>&nbsp;Q</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FADD&nbsp;&nbsp;&nbsp;&nbsp;st(i),st</tt></td><td><tt>DC C0+i</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FADD&nbsp;&nbsp;&nbsp;&nbsp;st,st(i)</tt></td><td><tt>D8 C0+i</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FADDP&nbsp;&nbsp;&nbsp;st(i),st</tt></td><td><tt>DE C0+i</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FBLD&nbsp;&nbsp;&nbsp;&nbsp;mtr</tt></td><td><tt>DF /4 d0 d1</tt></td><td>&nbsp;</td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FBSTP&nbsp;&nbsp;&nbsp;mtr</tt></td><td><tt>DF /6 d0 d1</tt></td><td>&nbsp;</td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FCHS</tt></td><td><tt>D9 E0</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FCLEX</tt></td><td><tt>9B DB E2</tt></td><td>&nbsp;</td><td><tt>3</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FCOM</tt></td><td><tt>D8 D1</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>-----z-p</tt></td></tr>
<tr><td><tt>FCOM&nbsp;&nbsp;&nbsp;&nbsp;mdr</tt></td><td><tt>D8 /2 d0 d1</tt></td><td><tt>&nbsp;D</tt></td><td><tt>2~4</tt></td><td><tt>-----z-p</tt></td></tr>
<tr><td><tt>FCOM&nbsp;&nbsp;&nbsp;&nbsp;mqr</tt></td><td><tt>DC /2 d0 d1</tt></td><td><tt>&nbsp;Q</tt></td><td><tt>2~4</tt></td><td><tt>-----z-p</tt></td></tr>
<tr><td><tt>FCOM&nbsp;&nbsp;&nbsp;&nbsp;st(i)</tt></td><td><tt>D8 D0+i</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>-----z-p</tt></td></tr>
<tr><td><tt>FCOMP</tt></td><td><tt>D8 D9</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>-----z-p</tt></td></tr>
<tr><td><tt>FCOMP&nbsp;&nbsp;&nbsp;mdr</tt></td><td><tt>D8 /3 d0 d1</tt></td><td><tt>&nbsp;D</tt></td><td><tt>2~4</tt></td><td><tt>-----z-p</tt></td></tr>
<tr><td><tt>FCOMP&nbsp;&nbsp;&nbsp;mqr</tt></td><td><tt>DC /3 d0 d1</tt></td><td><tt>&nbsp;Q</tt></td><td><tt>2~4</tt></td><td><tt>-----z-p</tt></td></tr>
<tr><td><tt>FCOMP&nbsp;&nbsp;&nbsp;st(i)</tt></td><td><tt>D8 D8+i</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>-----z-p</tt></td></tr>
<tr><td><tt>FCOMPP</tt></td><td><tt>DE D9</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>-----z-p</tt></td></tr>
<tr><td><tt>FCOS&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[387]</tt></td><td><tt>D9 FF</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FDECSTP</tt></td><td><tt>D9 F6</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FDISI</tt></td><td><tt>9B DB E1</tt></td><td>&nbsp;</td><td><tt>3</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FDIV&nbsp;&nbsp;&nbsp;&nbsp;mdr</tt></td><td><tt>D8 /6 d0 d1</tt></td><td><tt>&nbsp;D</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FDIV&nbsp;&nbsp;&nbsp;&nbsp;mqr</tt></td><td><tt>DC /6 d0 d1</tt></td><td><tt>&nbsp;Q</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FDIV&nbsp;&nbsp;&nbsp;&nbsp;st(i),st</tt></td><td><tt>DC F8+i</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FDIV&nbsp;&nbsp;&nbsp;&nbsp;st,st(i)</tt></td><td><tt>DC F0+i</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FDIVP</tt></td><td><tt>DE F9</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FDIVP&nbsp;&nbsp;&nbsp;st(i),st</tt></td><td><tt>DE F8+i</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FDIVR&nbsp;&nbsp;&nbsp;mdr</tt></td><td><tt>D8 /7 d0 d1</tt></td><td><tt>&nbsp;D</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FDIVR&nbsp;&nbsp;&nbsp;mqr</tt></td><td><tt>DC /7 d0 d1</tt></td><td><tt>&nbsp;Q</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FDIVR&nbsp;&nbsp;&nbsp;st(i),st</tt></td><td><tt>DC F0+i</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FDIVR&nbsp;&nbsp;&nbsp;st,st(i)</tt></td><td><tt>DC F8+i</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FDIVRP</tt></td><td><tt>DE F1</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FDIVRP&nbsp;&nbsp;st(i),st</tt></td><td><tt>DE F0+i</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FENI</tt></td><td><tt>9B DB E0</tt></td><td>&nbsp;</td><td><tt>3</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FFREE&nbsp;&nbsp;&nbsp;st(i)</tt></td><td><tt>DD C0+i</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FIADD&nbsp;&nbsp;&nbsp;mw</tt></td><td><tt>DE /0 d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FIADD&nbsp;&nbsp;&nbsp;md</tt></td><td><tt>DA /0 d0 d1</tt></td><td><tt>&nbsp;D</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FICOM&nbsp;&nbsp;&nbsp;mdr</tt></td><td><tt>DE /2 d0 d1</tt></td><td><tt>&nbsp;D</tt></td><td><tt>2~4</tt></td><td><tt>-----z-p</tt></td></tr>
<tr><td><tt>FICOM&nbsp;&nbsp;&nbsp;mqr</tt></td><td><tt>DA /2 d0 d1</tt></td><td><tt>&nbsp;Q</tt></td><td><tt>2~4</tt></td><td><tt>-----z-p</tt></td></tr>
<tr><td><tt>FICOMP&nbsp;&nbsp;md</tt></td><td><tt>DE /3 d0 d1</tt></td><td><tt>&nbsp;D</tt></td><td><tt>2~4</tt></td><td><tt>-----z-p</tt></td></tr>
<tr><td><tt>FICOMP&nbsp;&nbsp;mq</tt></td><td><tt>DA /3 d0 d1</tt></td><td><tt>&nbsp;Q</tt></td><td><tt>2~4</tt></td><td><tt>-----z-p</tt></td></tr>
<tr><td><tt>FIDIV&nbsp;&nbsp;&nbsp;mw</tt></td><td><tt>DE /6 d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FIDIV&nbsp;&nbsp;&nbsp;md</tt></td><td><tt>DA /6 d0 d1</tt></td><td><tt>&nbsp;D</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FIDIVR&nbsp;&nbsp;mw</tt></td><td><tt>DE /7 d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FIDIVR&nbsp;&nbsp;md</tt></td><td><tt>DA /7 d0 d1</tt></td><td><tt>&nbsp;D</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FILD&nbsp;&nbsp;&nbsp;&nbsp;mw</tt></td><td><tt>DF /0 d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FILD&nbsp;&nbsp;&nbsp;&nbsp;md</tt></td><td><tt>DB /0 d0 d1</tt></td><td><tt>&nbsp;D</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FILD&nbsp;&nbsp;&nbsp;&nbsp;mq</tt></td><td><tt>DF /5 d0 d1</tt></td><td><tt>&nbsp;Q</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FIMUL&nbsp;&nbsp;&nbsp;mw</tt></td><td><tt>DE /1 d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FIMUL&nbsp;&nbsp;&nbsp;md</tt></td><td><tt>DA /1 d0 d1</tt></td><td><tt>&nbsp;D</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FINCSTP</tt></td><td><tt>D9 F7</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FINIT</tt></td><td><tt>9B DB E3</tt></td><td>&nbsp;</td><td><tt>3</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FIST&nbsp;&nbsp;&nbsp;&nbsp;mw</tt></td><td><tt>DF /2 d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FIST&nbsp;&nbsp;&nbsp;&nbsp;md</tt></td><td><tt>DB /2 d0 d1</tt></td><td><tt>&nbsp;D</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FISTP&nbsp;&nbsp;&nbsp;mw</tt></td><td><tt>DF /3 d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FISTP&nbsp;&nbsp;&nbsp;md</tt></td><td><tt>DB /3 d0 d1</tt></td><td><tt>&nbsp;D</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FISTP&nbsp;&nbsp;&nbsp;mq</tt></td><td><tt>DF /7 d0 d1</tt></td><td><tt>&nbsp;Q</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FISUB&nbsp;&nbsp;&nbsp;mw</tt></td><td><tt>DE /4 d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FISUB&nbsp;&nbsp;&nbsp;md</tt></td><td><tt>DA /4 d0 d1</tt></td><td><tt>&nbsp;D</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FISUBR&nbsp;&nbsp;mw</tt></td><td><tt>DE /5 d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FISUBR&nbsp;&nbsp;md</tt></td><td><tt>DA /5 d0 d1</tt></td><td><tt>&nbsp;D</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FLD&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;mdr</tt></td><td><tt>D9 /0 d0 d1</tt></td><td><tt>&nbsp;D</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FLD&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;mqr</tt></td><td><tt>DD /0 d0 d1</tt></td><td><tt>&nbsp;Q</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FLD&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;mtr</tt></td><td><tt>DB /5 d0 d1</tt></td><td><tt>&nbsp;T</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FLD&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;st(i)</tt></td><td><tt>D9 C0+i</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FLD1</tt></td><td><tt>D9 E8</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FLDCW&nbsp;&nbsp;&nbsp;mw</tt></td><td><tt>D9 /5 d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FLDENV&nbsp;&nbsp;m14</tt></td><td><tt>D9 /4 d0 d1</tt></td><td>&nbsp;</td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FLDL2E</tt></td><td><tt>D9 EA</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FLDL2T</tt></td><td><tt>D9 E9</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FLDLG2</tt></td><td><tt>D9 EC</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FLDLN2</tt></td><td><tt>D9 ED</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FLDPI</tt></td><td><tt>D9 EB</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FLDZ</tt></td><td><tt>D9 EE</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FMUL</tt></td><td><tt>DE C9</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FMUL&nbsp;&nbsp;&nbsp;&nbsp;mdr</tt></td><td><tt>D8 /1 d0 d1</tt></td><td><tt>&nbsp;D</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FMUL&nbsp;&nbsp;&nbsp;&nbsp;mqr</tt></td><td><tt>DC /1 d0 d1</tt></td><td><tt>&nbsp;Q</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FMUL&nbsp;&nbsp;&nbsp;&nbsp;st(i),st</tt></td><td><tt>DC C8+i</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FMUL&nbsp;&nbsp;&nbsp;&nbsp;st,st(i)</tt></td><td><tt>D8 C8+i</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FMULP&nbsp;&nbsp;&nbsp;st(i),st</tt></td><td><tt>DE C8+i</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FNCLEX</tt></td><td><tt>DB E2</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FNDISI</tt></td><td><tt>DB E1</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FNENI</tt></td><td><tt>DB E0</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FNINIT</tt></td><td><tt>DB E3</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FNOP</tt></td><td><tt>D9 D0</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FNSAVE&nbsp;&nbsp;m94</tt></td><td><tt>DD /6 d0 d1</tt></td><td>&nbsp;</td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FNSTCW&nbsp;&nbsp;mw</tt></td><td><tt>D9 /7 d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FNSTENV&nbsp;m14</tt></td><td><tt>D9 /6 d0 d1</tt></td><td>&nbsp;</td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FNSTSW&nbsp;&nbsp;ax</tt></td><td><tt>DF E0</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FNSTSW&nbsp;&nbsp;mw</tt></td><td><tt>DD /7 d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FPATAN</tt></td><td><tt>D9 F3</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FPREM</tt></td><td><tt>D9 F8</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FPREM1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[387]</tt></td><td><tt>D9 F5</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FPTAN</tt></td><td><tt>D9 F2</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FRNDINT</tt></td><td><tt>D9 FC</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FRSTOR&nbsp;&nbsp;m94</tt></td><td><tt>DD /4 d0 d1</tt></td><td>&nbsp;</td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FSAVE&nbsp;&nbsp;&nbsp;m94</tt></td><td><tt>9B DD /6 d0 d1</tt></td><td>&nbsp;</td><td><tt>3~5</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FSCALE</tt></td><td><tt>D9 FD</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FSETPM</tt></td><td><tt>DB E4</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FSIN&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[387]</tt></td><td><tt>D9 FE</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FSINCOS&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[387]</tt></td><td><tt>D9 FB</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FSQRT</tt></td><td><tt>D9 FA</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FST&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;mdr</tt></td><td><tt>D9 /2 d0 d1</tt></td><td><tt>&nbsp;D</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FST&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;mqr</tt></td><td><tt>DD /2 d0 d1</tt></td><td><tt>&nbsp;Q</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FST&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;st(i)</tt></td><td><tt>DD D0+i</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FSTCW&nbsp;&nbsp;&nbsp;mw</tt></td><td><tt>9B D9 /7 d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>3~5</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FSTENV&nbsp;&nbsp;m14</tt></td><td><tt>9B D9 /6 d0 d1</tt></td><td>&nbsp;</td><td><tt>3~5</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FSTP&nbsp;&nbsp;&nbsp;&nbsp;mdr</tt></td><td><tt>D9 /3 d0 d1</tt></td><td><tt>&nbsp;D</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FSTP&nbsp;&nbsp;&nbsp;&nbsp;mqr</tt></td><td><tt>DD /3 d0 d1</tt></td><td><tt>&nbsp;Q</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FSTP&nbsp;&nbsp;&nbsp;&nbsp;mtr</tt></td><td><tt>DB /7 d0 d1</tt></td><td><tt>&nbsp;T</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FSTP&nbsp;&nbsp;&nbsp;&nbsp;st(i)</tt></td><td><tt>DD D8+i</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FSTSW&nbsp;&nbsp;&nbsp;ax</tt></td><td><tt>9B DF E0</tt></td><td>&nbsp;</td><td><tt>3</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FSTSW&nbsp;&nbsp;&nbsp;mw</tt></td><td><tt>9B DD /7 d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>3~5</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FSUB&nbsp;&nbsp;&nbsp;&nbsp;mdr</tt></td><td><tt>D8 /4 d0 d1</tt></td><td><tt>&nbsp;D</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FSUB&nbsp;&nbsp;&nbsp;&nbsp;mqr</tt></td><td><tt>DC /4 d0 d1</tt></td><td><tt>&nbsp;Q</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FSUB&nbsp;&nbsp;&nbsp;&nbsp;st(i),st</tt></td><td><tt>DC E8+i</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FSUB&nbsp;&nbsp;&nbsp;&nbsp;st,st(i)</tt></td><td><tt>D8 E0+i</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FSUBP</tt></td><td><tt>DE E9</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FSUBP&nbsp;&nbsp;&nbsp;st(i),st</tt></td><td><tt>DE E8+i</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FSUBR</tt></td><td><tt>DE E1</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FSUBR&nbsp;&nbsp;&nbsp;mdr</tt></td><td><tt>D8 /5 d0 d1</tt></td><td><tt>&nbsp;D</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FSUBR&nbsp;&nbsp;&nbsp;mqr</tt></td><td><tt>DC /5 d0 d1</tt></td><td><tt>&nbsp;Q</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FSUBR&nbsp;&nbsp;&nbsp;st(i),st</tt></td><td><tt>DC E0+i</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FSUBR&nbsp;&nbsp;&nbsp;st,st(i)</tt></td><td><tt>D8 E8+i</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FSUBRP&nbsp;&nbsp;st(i),st</tt></td><td><tt>DE E0+i</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FTST</tt></td><td><tt>D9 E4</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FUCOM&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[387]</tt></td><td><tt>DD E1</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>-----z-p</tt></td></tr>
<tr><td><tt>FUCOM&nbsp;&nbsp;&nbsp;st(i)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[387]</tt></td><td><tt>DD E0+i</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>-----z-p</tt></td></tr>
<tr><td><tt>FUCOMP&nbsp;&nbsp;st(i)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[387]</tt></td><td><tt>DD E8+i</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>-----z-p</tt></td></tr>
<tr><td><tt>FUCOMPP&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[387]</tt></td><td><tt>DA E9</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>-----z-p</tt></td></tr>
<tr><td><tt>FXAM</tt></td><td><tt>D9 E5</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FXCH</tt></td><td><tt>D9 C9</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FXCH&nbsp;&nbsp;&nbsp;&nbsp;st(i)</tt></td><td><tt>D9 C8+i</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FXTRACT</tt></td><td><tt>D9 F4</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FYL2X</tt></td><td><tt>D9 F1</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>FYL2XP1</tt></td><td><tt>D9 F9</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>

<h4><a name="esc">ESC - Escape</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>ESC</tt></td><td><tt>?</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>ESC&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;immed,src</tt></dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Provides access to the data bus for other resident processors.<br>
The CPU treats it as a NOP but places memory operand on bus.
</p></div>

<h4><a name="hlt">HLT - Halt CPU</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>HLT</tt></td><td><tt>F4</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>HLT</tt></dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Halts CPU until RESET line is activated, NMI or maskable interrupt<br>
received.  The CPU becomes dormant but retains the current CS:IP<br>
for later restart.
</p></div>

<h4><a name="idiv">IDIV - Signed Integer Division</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>IDIV&nbsp;&nbsp;&nbsp;&nbsp;rmb</tt></td><td><tt>F6 /7 d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2~4</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>IDIV&nbsp;&nbsp;&nbsp;&nbsp;rmw</tt></td><td><tt>F7 /7 d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>o---szap</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>IDIV&nbsp;&nbsp;&nbsp;src</tt></dd>
<dt>Modifies flags</dt><dd>(AF,CF,OF,PF,SF,ZF undefined)</dd>
</dl>
<p>
Signed binary division of accumulator by source.  If source is a<br>
byte value, AX is divided by "src" and the quotient is stored in<br>
AL and the remainder in AH.  If source is a word value, DX:AX is<br>
divided by "src", and the quotient is stored in AL and the<br>
remainder in DX.
</p></div>

<h4><a name="imul">IMUL - Signed Multiply</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>IMUL&nbsp;&nbsp;&nbsp;&nbsp;rb,rmb&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F AF mr d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>3~5</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>IMUL&nbsp;&nbsp;&nbsp;&nbsp;rd,ib</tt></td><td><tt>6B mr i0</tt></td><td><tt>&nbsp;W</tt></td><td><tt>3</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>IMUL&nbsp;&nbsp;&nbsp;&nbsp;rd,id</tt></td><td><tt>69 mr i0 i1 i2 i3</tt></td><td><tt>&nbsp;W</tt></td><td><tt>6</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>IMUL&nbsp;&nbsp;&nbsp;&nbsp;rd,rmd,ib</tt></td><td><tt>6B mr d0 d1 i0</tt></td><td><tt>&nbsp;W</tt></td><td><tt>3~5</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>IMUL&nbsp;&nbsp;&nbsp;&nbsp;rd,rmd,id</tt></td><td><tt>69 mr d0 d1 i0~i3</tt></td><td><tt>&nbsp;W</tt></td><td><tt>6~8</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>IMUL&nbsp;&nbsp;&nbsp;&nbsp;rmb</tt></td><td><tt>F6 /5 d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2~4</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>IMUL&nbsp;&nbsp;&nbsp;&nbsp;rmw</tt></td><td><tt>F7 /5 d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>IMUL&nbsp;&nbsp;&nbsp;&nbsp;rw,ib</tt></td><td><tt>6B mr i0</tt></td><td><tt>&nbsp;B</tt></td><td><tt>3</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>IMUL&nbsp;&nbsp;&nbsp;&nbsp;rw,iw</tt></td><td><tt>69 mr i0 i1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>4</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>IMUL&nbsp;&nbsp;&nbsp;&nbsp;rw,rmw&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F AF mr d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>3~5</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>IMUL&nbsp;&nbsp;&nbsp;&nbsp;rw,rmw,ib</tt></td><td><tt>6B mr d0 d1 i0</tt></td><td><tt>&nbsp;B</tt></td><td><tt>3~5</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>IMUL&nbsp;&nbsp;&nbsp;&nbsp;rw,rmw,iw</tt></td><td><tt>69 mr d0 d1 i0 i1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>4~6</tt></td><td><tt>o---szap</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>IMUL&nbsp;&nbsp;&nbsp;&nbsp;src</tt><br>
<tt>IMUL&nbsp;&nbsp;&nbsp;&nbsp;src,immed&nbsp;&nbsp;(286+&nbsp;only)</tt>
<br>
<tt>IMUL&nbsp;&nbsp;&nbsp;&nbsp;dest,src,immed8&nbsp;&nbsp;(286+&nbsp;only)</tt>
<br>
<tt>IMUL&nbsp;&nbsp;&nbsp;&nbsp;dest,src&nbsp;&nbsp;(386+&nbsp;only)</tt>
</dd>
<dt>Modifies flags</dt><dd>CF OF (AF,PF,SF,ZF undefined)</dd>
</dl>
<p>
Signed multiplication of accumulator by "src" with result placed<br>
in the accumulator.  If the source operand is a byte value, it<br>
is multiplied by AL and the result stored in AX.  If the source<br>
operand is a word value it is multiplied by AX and the result is<br>
stored in DX:AX.  Other variations of this instruction allow<br>
specification of source and destination registers as well as a<br>
third immediate factor.
</p></div>

<h4><a name="in">IN - Input Byte or Word From Port</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>IN&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;AL,ib</tt></td><td><tt>E4 i0</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>IN&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;AL,DX</tt></td><td><tt>EC</tt></td><td><tt>&nbsp;B</tt></td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>IN&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;AX,ib</tt></td><td><tt>E5 i0</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>IN&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;AX,DX</tt></td><td><tt>ED</tt></td><td><tt>&nbsp;W</tt></td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>IN&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;accum,port</tt></dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
A byte, word or dword is read from "port" and placed in AL, AX or<br>
EAX respectively.  If the port number is in the range of 0-255<br>
it can be specified as an immediate, otherwise the port number<br>
must be specified in DX.  Valid port ranges on the PC are 0-1024,<br>
though values through 65535 may be specified and recognized by<br>
third party vendors and PS/2's.
</p></div>

<h4><a name="inc">INC - Increment</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>INC&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;AX</tt></td><td><tt>40</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>INC&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;CX</tt></td><td><tt>41</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>INC&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DX</tt></td><td><tt>42</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>INC&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;BX</tt></td><td><tt>43</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>INC&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;SP</tt></td><td><tt>44</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>INC&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;BP</tt></td><td><tt>45</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>INC&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;SI</tt></td><td><tt>46</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>INC&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DI</tt></td><td><tt>47</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>INC&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb</tt></td><td><tt>FE /0 d0 d1</tt></td><td>&nbsp;</td><td><tt>2~4</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>INC&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw</tt></td><td><tt>FF /0 d0 d1</tt></td><td>&nbsp;</td><td><tt>2~4</tt></td><td><tt>o---szap</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>INC&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dest</tt></dd>
<dt>Modifies flags</dt><dd>AF OF PF SF ZF</dd>
</dl>
<p>
Adds one to destination unsigned binary operand.
</p></div>

<h4><a name="ins">INS - Input String from Port  (80188+)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>INSB&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[186]</tt></td><td><tt>6C</tt></td><td><tt>&nbsp;B</tt></td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>INSW&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[186]</tt></td><td><tt>6D</tt></td><td><tt>&nbsp;W</tt></td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>INSD&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[32bit]</tt></td><td><tt>66| 6D</tt></td><td><tt>&nbsp;D</tt></td><td><tt>1+1</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>INS&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dest,port</tt><br>
<tt>INSB</tt>
<br>
<tt>INSW</tt>
<br>
<tt>INSD&nbsp;&nbsp;(386+&nbsp;only)</tt>
</dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Loads data from port to the destination ES:(E)DI (even if a<br>
destination operand is supplied). (E)DI is adjusted by the size<br>
of the operand and increased if the Direction Flag is cleared and<br>
decreased if the Direction Flag is set.  For INSB, INSW, INSD no<br>
operands are allowed and the size is determined by the mnemonic.
</p></div>

<h4><a name="int">INT - Interrupt</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>INT&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3</tt></td><td><tt>CC</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--00----</tt></td></tr>
<tr><td><tt>INT&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ib</tt></td><td><tt>CD i0</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--00----</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>INT&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;num</tt></dd>
<dt>Modifies flags</dt><dd>TF IF</dd>
</dl>
<p>
Initiates a software interrupt by pushing the flags, clearing the<br>
Trap and Interrupt Flags, pushing CS followed by IP and loading<br>
CS:IP with the value found in the interrupt vector table.  Execution<br>
then begins at the location addressed by the new CS:IP
</p></div>

<h4><a name="into">INTO - Interrupt on Overflow</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>INTO</tt></td><td><tt>CE</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--00----</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>INTO</tt></dd>
<dt>Modifies flags</dt><dd>IF TF</dd>
</dl>
<p>
If the Overflow Flag is set this instruction generates an INT 4<br>
which causes the code addressed by 0000:0010 to be executed.
</p></div>

<h4><a name="invd">INVD - Invalidate Cache  (486+ only)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>INVD&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[486]</tt></td><td><tt>0F 08</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>INVD</tt></dd>
<dt>Modifies flags</dt><dd>none</dd>
</dl>
<p>
Flushes CPU internal cache.  Issues special function bus cycle<br>
which indicates to flush external caches.   Data in write-back<br>
external caches is lost.
<br>
</p></div>

<h4><a name="invlpg">INVLPG - Invalidate Translation Look-Aside Buffer Entry  (486+ only)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>INVLPG&nbsp;&nbsp;m&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[486]</tt></td><td><tt>0F 01 /7</tt></td><td>&nbsp;</td><td><tt>3</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>INVLPG</tt></dd>
<dt>Modifies flags</dt><dd>none</dd>
</dl>
<p>
Invalidates a single page table entry in the Translation<br>
Look-Aside Buffer.  Intel warns that this instruction may be<br>
implemented differently on future processors.
</p></div>

<h4><a name="iret">IRET/IRETD - Interrupt Return</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>IRET</tt></td><td><tt>CF</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>oditszap</tt></td></tr>
<tr><td><tt>IRETD&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[32bit]</tt></td><td><tt>66| CF</tt></td><td>&nbsp;</td><td><tt>1+1</tt></td><td><tt>oditszap</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>IRET</tt><br>
<tt>IRETD&nbsp;&nbsp;(386+&nbsp;only)</tt>
</dd>
<dt>Modifies flags</dt><dd>AF CF DF IF PF SF TF ZF</dd>
</dl>
<p>
Returns control to point of interruption by popping IP, CS<br>
and then the Flags from the stack and continues execution at<br>
this location.  CPU exception interrupts will return to the<br>
instruction that cause the exception because the CS:IP placed<br>
on the stack during the interrupt is the address of the offending<br>
instruction.
</p></div>

<h4><a name="ja">JA/JNBE - Jump Above / Jump Not Below or Equal</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>JA&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ll&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F 87 r0 r1</tt></td><td>&nbsp;</td><td><tt>4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>JA&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sl</tt></td><td><tt>77 r0</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>JA&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;label</tt><br>
<tt>JNBE&nbsp;&nbsp;&nbsp;&nbsp;label</tt>
</dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Causes execution to branch to "label" if the Carry Flag and Zero Flag<br>
are both clear.  Unsigned comparison.
</p><p>
<sup>*)</sup>&nbsp;JA/JNBE are different mnemonics for the same instruction
</p></div>

<h4><a name="jae">JAE/JNB - Jump Above or Equal / Jump on Not Below</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>JAE&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ll&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F 83 r0 r1</tt></td><td>&nbsp;</td><td><tt>4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>JAE&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sl</tt></td><td><tt>73 r0</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>JAE&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;label</tt><br>
<tt>JNB&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;label</tt>
</dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Causes execution to branch to "label" if the Carry Flag is clear.<br>
Functionally similar to JNC.  Unsigned comparison.
</p><p>
<sup>*)</sup>&nbsp;JAE/JNB are different mnemonics for the same instruction
</p></div>

<h4><a name="jb">JB/JNAE - Jump Below / Jump Not Above or Equal</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>JB&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ll&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F 82 r0 r1</tt></td><td>&nbsp;</td><td><tt>4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>JB&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sl</tt></td><td><tt>72 r0</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>JB&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;label</tt><br>
<tt>JNAE&nbsp;&nbsp;&nbsp;&nbsp;label</tt>
</dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Causes execution to branch to "label" if the Carry Flag is set.<br>
Functionally similar to JC.  Unsigned comparison.
</p><p>
<sup>*)</sup>&nbsp;JB/JNAE are different mnemonics for the same instruction
</p></div>

<h4><a name="jbe">JBE/JNA - Jump Below or Equal / Jump Not Above</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>JBE&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ll&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F 86 r0 r1</tt></td><td>&nbsp;</td><td><tt>4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>JBE&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sl</tt></td><td><tt>76 r0</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>JBE&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;label</tt><br>
<tt>JNA&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;label</tt>
</dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Causes execution to branch to "label" if the Carry Flag or<br>
the Zero Flag is set.   Unsigned comparison.
</p><p>
<sup>*)</sup>&nbsp;JBE/JNA are different mnemonics for the same instruction
</p></div>

<h4><a name="jc">JC - Jump on Carry</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>JC&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ll&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F 82 r0 r1</tt></td><td>&nbsp;</td><td><tt>4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>JC&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sl</tt></td><td><tt>72 r0</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>JC&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;label</tt></dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Causes execution to branch to "label" if the Carry Flag is set.<br>
Functionally similar to JB and JNAE.  Unsigned comparison.
</p></div>

<h4><a name="jcxz">JCXZ/JECXZ - Jump if Register (E)CX is Zero</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>JCXZ&nbsp;&nbsp;&nbsp;&nbsp;sl</tt></td><td><tt>E3 r0</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>JECXZ&nbsp;&nbsp;&nbsp;sl&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[32bit]</tt></td><td><tt>67| E3 r0</tt></td><td>&nbsp;</td><td><tt>1+2</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>JCXZ&nbsp;&nbsp;&nbsp;&nbsp;label</tt><br>
<tt>JECXZ&nbsp;&nbsp;&nbsp;label&nbsp;&nbsp;(386+&nbsp;only)</tt>
</dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Causes execution to branch to "label" if register CX is zero.  Uses unsigned comparison.
</p></div>

<h4><a name="je">JE/JZ - Jump Equal / Jump Zero</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>JE&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ll&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F 84 r0 r1</tt></td><td>&nbsp;</td><td><tt>4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>JE&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sl</tt></td><td><tt>74 r0</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>JE&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;label</tt><br>
<tt>JZ&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;label</tt>
</dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Causes execution to branch to "label" if the Zero Flag is set.  Uses unsigned comparison.
</p><p>
<sup>*)</sup>&nbsp;JE/JZ are different mnemonics for the same instruction
</p></div>

<h4><a name="jg">JG/JNLE - Jump Greater / Jump Not Less or Equal</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>JG&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ll&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F 8F r0 r1</tt></td><td>&nbsp;</td><td><tt>4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>JG&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sl</tt></td><td><tt>7F r0</tt></td><td>&nbsp;</td><td><tt>4</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>JG&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;label</tt><br>
<tt>JNLE&nbsp;&nbsp;&nbsp;&nbsp;label</tt>
</dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Causes execution to branch to "label" if the Zero Flag is clear or<br>
the Sign Flag equals the Overflow Flag.  Signed comparison.
</p><p>
<sup>*)</sup>&nbsp;JG/JNLE are different mnemonics for the same instruction
</p></div>

<h4><a name="jge">JGE/JNL - Jump Greater or Equal / Jump Not Less</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>JGE&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ll&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F 8D r0 r1</tt></td><td>&nbsp;</td><td><tt>4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>JGE&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sl</tt></td><td><tt>7D r0</tt></td><td>&nbsp;</td><td><tt>4</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>JGE&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;label</tt><br>
<tt>JNL&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;label</tt>
</dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Causes execution to branch to "label" if the Sign Flag equals<br>
the Overflow Flag.  Signed comparison.
</p><p>
<sup>*)</sup>&nbsp;JGE/JNL are different mnemonics for the same instruction
</p></div>

<h4><a name="jl">JL/JNGE - Jump Less / Jump Not Greater or Equal</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>JL&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ll&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F 8C r0 r1</tt></td><td>&nbsp;</td><td><tt>4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>JL&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sl</tt></td><td><tt>7C r0</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>JL&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;label</tt><br>
<tt>JNGE&nbsp;&nbsp;&nbsp;&nbsp;label</tt>
</dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Causes execution to branch to "label" if the Sign Flag is not equal<br>
to Overflow Flag.  Unsigned comparison.
</p><p>
<sup>*)</sup>&nbsp;JL/JNGE are different mnemonics for the same instruction
</p></div>

<h4><a name="jle">JLE/JNG - Jump Less or Equal / Jump Not Greater</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>JLE&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ll&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F 8E r0 r1</tt></td><td>&nbsp;</td><td><tt>4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>JLE&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sl</tt></td><td><tt>7E r0</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>JLE&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;label</tt><br>
<tt>JNG&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;label</tt>
</dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Causes execution to branch to "label" if the Zero Flag is set or the<br>
Sign Flag is not equal to the Overflow Flag.  Signed comparison.
</p><p>
<sup>*)</sup>&nbsp;JLE/JNG are different mnemonics for the same instruction
</p></div>

<h4><a name="jmp">JMP - Unconditional Jump</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>JMP&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;SHORT&nbsp;sl</tt></td><td><tt>EB r0</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>JMP&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;np</tt></td><td><tt>E9 o0 o1</tt></td><td>&nbsp;</td><td><tt>3</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>JMP&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw</tt></td><td><tt>FF /4 d0 d1</tt></td><td>&nbsp;</td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>JMP&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DWORD&nbsp;PTR&nbsp;[rmw]</tt></td><td><tt>FF /5 d0 d1</tt></td><td>&nbsp;</td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>JMP&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;FAR&nbsp;PTR&nbsp;fp</tt></td><td><tt>EA o0 o1 s0 s1</tt></td><td>&nbsp;</td><td><tt>5</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>JMP&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;target</tt></dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Unconditionally transfers control to "label".  Jumps by default<br>
are within -32768 to 32767 bytes from the instruction following<br>
the jump.  NEAR and SHORT jumps cause the IP to be updated while FAR<br>
jumps cause CS and IP to be updated.
</p></div>

<h4><a name="jnc">JNC - Jump Not Carry</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>JNC&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ll&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F 83 r0 r1</tt></td><td>&nbsp;</td><td><tt>4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>JNC&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sl</tt></td><td><tt>73 r0</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>JNC&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;label</tt></dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Causes execution to branch to "label" if the Carry Flag is clear.<br>
Functionally similar to JAE or JNB.  Unsigned comparison.
</p></div>

<h4><a name="jne">JNE/JNZ - Jump Not Equal / Jump Not Zero</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>JNE&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ll&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F 85 r0 r1</tt></td><td>&nbsp;</td><td><tt>4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>JNE&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sl</tt></td><td><tt>75 r0</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>JNE&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;label</tt><br>
<tt>JNZ&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;label</tt>
</dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Causes execution to branch to "label" if the Zero Flag is clear. Unsigned comparison.
</p><p>
<sup>*)</sup>&nbsp;JNE/JNZ are different mnemonics for the same instruction
</p></div>

<h4><a name="jno">JNO - Jump Not Overflow</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>JNO&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ll&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F 81 r0 r1</tt></td><td>&nbsp;</td><td><tt>4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>JNO&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sl</tt></td><td><tt>71 r0</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>JNO&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;label</tt></dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Causes execution to branch to "label" if the Overflow Flag is clear. Signed comparison.
<br>
</p></div>

<h4><a name="jns">JNS - Jump Not Signed</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>JNS&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ll&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F 89 r0 r1</tt></td><td>&nbsp;</td><td><tt>4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>JNS&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sl</tt></td><td><tt>79 r0</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>JNS&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;label</tt></dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Causes execution to branch to "label" if the Sign Flag is clear. Signed comparison.
</p></div>

<h4><a name="jnp">JNP/JPO - Jump Not Parity / Jump Parity Odd</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>JNP&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ll&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F 8B r0 r1</tt></td><td>&nbsp;</td><td><tt>4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>JNP&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sl</tt></td><td><tt>7B r0</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>JNP&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;label</tt><br>
<tt>JPO&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;label</tt>
</dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Causes execution to branch to "label" if the Parity Flag is clear. Unsigned comparison.
</p><p>
<sup>*)</sup>&nbsp;JNE/JPO are different mnemonics for the same instruction
</p></div>

<h4><a name="jo">JO - Jump on Overflow</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>JO&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ll&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F 80 r0 r1</tt></td><td>&nbsp;</td><td><tt>4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>JO&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sl</tt></td><td><tt>70 r0</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>JO&nbsp;&nbsp;label</tt></dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Causes execution to branch to "label" if the Overflow Flag is set. Signed comparison.
</p></div>

<h4><a name="jp">JP/JPE - Jump on Parity / Jump on Parity Even</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>JP&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ll&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F 8A r0 r1</tt></td><td>&nbsp;</td><td><tt>4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>JP&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sl</tt></td><td><tt>7A r0</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>JP&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;label</tt><br>
<tt>JPE&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;label</tt>
</dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Causes execution to branch to "label" if the Parity Flag is set. Unsigned comparison.
</p><p>
<sup>*)</sup>&nbsp;JP/JPE are different mnemonics for the same instruction
</p></div>

<h4><a name="js">JS - Jump Signed</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>JS&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ll&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F 88 r0 r1</tt></td><td>&nbsp;</td><td><tt>4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>JS&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sl</tt></td><td><tt>78 r0</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>JS&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;label</tt></dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Causes execution to branch to "label" if the Sign Flag is set. Signed comparison.
</p></div>

<h4><a name="lahf">LAHF - Load Register AH From Flags</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>LAHF</tt></td><td><tt>9F</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>LAHF</tt></dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Copies bits 0-7 of the flags register into AH.  This includes flags<br>
AF, CF, PF, SF and ZF other bits are undefined.
</p></div>

<h4><a name="lar">LAR - Load Access Rights  (286+ protected)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>LAR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rw,rmw&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[286]</tt></td><td><tt>0F 02 mr d0 d1</tt></td><td>&nbsp;</td><td><tt>3~5</tt></td><td><tt>-----z--</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>LAR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dest,src</tt></dd>
<dt>Modifies flags</dt><dd>ZF</dd>
</dl>
<p>
The high byte of the of the destination register is overwritten by<br>
the value of the access rights byte and the low order byte is zeroed<br>
depending on the selection in the source operand.  The Zero Flag is<br>
set if the load operation is successful.
</p></div>

<h4><a name="lds">LDS - Load Pointer Using DS</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>LDS&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rw,md</tt></td><td><tt>C5 mr d0 d1</tt></td><td>&nbsp;</td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>LDS&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dest,src</tt></dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Loads 32-bit pointer from memory source to destination register<br>
and DS.  The offset is placed in the destination register and the<br>
segment is placed in DS.  To use this instruction the word at the<br>
lower memory address must contain the offset and the word at the<br>
higher address must contain the segment.  This simplifies the loading<br>
of far pointers from the stack and the interrupt vector table.
</p></div>

<h4><a name="lea">LEA - Load Effective Address</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>LEA&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rw,mw</tt></td><td><tt>8D mr d0 d1</tt></td><td>&nbsp;</td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>LEA&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dest,src</tt></dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Transfers offset address of "src" to the destination register.
</p></div>

<h4><a name="leave">LEAVE - Restore Stack for Procedure Exit  (80188+)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>LEAVE&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[186]</tt></td><td><tt>C9</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>LEAVE</tt></dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Releases the local variables created by the previous ENTER<br>
instruction by restoring SP and BP to their condition before<br>
the procedure stack frame was initialized.
</p></div>

<h4><a name="les">LES - Load Pointer Using ES</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>LES&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rw,md</tt></td><td><tt>C4 mr d0 d1</tt></td><td>&nbsp;</td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>LES&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dest,src</tt></dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Loads 32-bit pointer from memory source to destination register<br>
and ES.  The offset is placed in the destination register and the<br>
segment is placed in ES.  To use this instruction the word at the<br>
lower memory address must contain the offset and the word at the<br>
higher address must contain the segment.  This simplifies the loading<br>
of far pointers from the stack and the interrupt vector table.
</p></div>

<h4><a name="lfs">LFS - Load Pointer Using FS  (386+ only)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>LFS&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rw,md&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F B4 mr d0 d1</tt></td><td>&nbsp;</td><td><tt>3~5</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>LFS&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dest,src</tt></dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Loads 32-bit pointer from memory source to destination register<br>
and FS.  The offset is placed in the destination register and the<br>
segment is placed in FS.  To use this instruction the word at the<br>
lower memory address must contain the offset and the word at the<br>
higher address must contain the segment.  This simplifies the loading<br>
of far pointers from the stack and the interrupt vector table.
</p></div>

<h4><a name="lgdt">LGDT - Load Global Descriptor Table  (286+ privileged)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>LGDT&nbsp;&nbsp;&nbsp;&nbsp;mw&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[286]</tt></td><td><tt>0F 01 /2 d0 d1</tt></td><td>&nbsp;</td><td><tt>3~5</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>LGDT&nbsp;&nbsp;&nbsp;&nbsp;src</tt></dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Loads a value from an operand into the Global Descriptor Table (GDT) register.
</p></div>

<h4><a name="lidt">LIDT - Load Interrupt Descriptor Table  (286+ privileged)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>LIDT&nbsp;&nbsp;&nbsp;&nbsp;mw&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[286]</tt></td><td><tt>0F 01 /3 d0 d1</tt></td><td>&nbsp;</td><td><tt>3~5</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>LIDT&nbsp;&nbsp;&nbsp;&nbsp;src</tt></dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Loads a value from an operand into the Interrupt Descriptor Table (IDT) register.
</p></div>

<h4><a name="lgs">LGS - Load Pointer Using GS  (386+ only)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>LGS&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rw,md&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F B5 mr d0 d1</tt></td><td>&nbsp;</td><td><tt>3~5</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>LGS&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dest,src</tt></dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Loads 32-bit pointer from memory source to destination register<br>
and GS.  The offset is placed in the destination register and the<br>
segment is placed in GS.  To use this instruction the word at the<br>
lower memory address must contain the offset and the word at the<br>
higher address must contain the segment.  This simplifies the loading<br>
of far pointers from the stack and the interrupt vector table.
</p></div>

<h4><a name="lldt">LLDT - Load Local Descriptor Table  (286+ privileged)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>LLDT&nbsp;&nbsp;&nbsp;&nbsp;rmw&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[286]</tt></td><td><tt>0F 00 /2 d0 d1</tt></td><td>&nbsp;</td><td><tt>3~5</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>LLDT&nbsp;&nbsp;&nbsp;&nbsp;src</tt></dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Loads a value from an operand into the Local Descriptor Table Register (LDTR).
</p></div>

<h4><a name="lmsw">LMSW - Load Machine Status Word  (286+ privileged)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>LMSW&nbsp;&nbsp;&nbsp;&nbsp;rmw&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[286]</tt></td><td><tt>0F 01 /6 d0 d1</tt></td><td>&nbsp;</td><td><tt>3~5</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>LMSW&nbsp;&nbsp;&nbsp;&nbsp;src</tt></dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Loads the Machine Status Word (MSW) from data found at "src"
</p></div>

<h4><a name="lock">LOCK - Lock Bus</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>LOCK</tt></td><td><tt>F0</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>LOCK</tt><br>
<tt>LOCK:&nbsp;(386+&nbsp;prefix)</tt>
</dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
This instruction is a prefix that causes the CPU assert bus lock<br>
signal during the execution of the next instruction.  Used to<br>
avoid two processors from updating the same data location.  The<br>
286 always asserts lock during an XCHG with memory operands.  This<br>
should only be used to lock the bus prior to XCHG, MOV, IN and<br>
OUT instructions.
</p></div>

<h4><a name="lods">LODS - Load String (Byte, Word or Double)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>LODSB</tt></td><td><tt>AC</tt></td><td><tt>&nbsp;B</tt></td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>LODSW</tt></td><td><tt>AD</tt></td><td><tt>&nbsp;W</tt></td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>LODSD&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[32bit]</tt></td><td><tt>66| AD</tt></td><td><tt>&nbsp;D</tt></td><td><tt>1+1</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>LODS&nbsp;&nbsp;&nbsp;&nbsp;src</tt><br>
<tt>LODSB</tt>
<br>
<tt>LODSW</tt>
<br>
<tt>LODSD&nbsp;&nbsp;(386+&nbsp;only)</tt>
</dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Transfers string element addressed by DS:SI (even if an operand is<br>
supplied) to the accumulator.   SI is incremented based on the size<br>
of the operand or based on the instruction used.  If the Direction<br>
Flag is set SI is decremented, if the Direction Flag is clear SI<br>
is incremented.  Use with REP prefixes.
</p></div>

<h4><a name="loop">LOOP - Decrement CX and Loop if CX Not Zero</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>LOOP&nbsp;&nbsp;&nbsp;&nbsp;sl</tt></td><td><tt>E2 r0</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>LOOP&nbsp;&nbsp;&nbsp;&nbsp;label</tt></dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Decrements CX by 1 and transfers control to "label" if CX is not<br>
Zero.  The "label" operand must be within -128 or 127 bytes of the<br>
instruction following the loop instruction
</p></div>

<h4><a name="loope">LOOPE/LOOPZ - Loop While Equal / Loop While Zero</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>LOOPE&nbsp;&nbsp;&nbsp;sl</tt></td><td><tt>E1 r0</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>LOOPE&nbsp;&nbsp;&nbsp;label</tt><br>
<tt>LOOPZ&nbsp;&nbsp;&nbsp;label</tt>
</dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Decrements CX by 1 (without modifying the flags) and transfers<br>
control to "label" if CX != 0 and the Zero Flag is set.  The<br>
"label" operand must be within -128 or 127 bytes of the instruction<br>
following the loop instruction.<br>
</p><p>
<sup>*)</sup>&nbsp;LOOPE/LOOPZ are different mnemonics for the same instruction
</p></div>

<h4><a name="loopnz">LOOPNZ/LOOPNE - Loop While Not Zero / Loop While Not Equal</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>LOOPNZ&nbsp;&nbsp;sl</tt></td><td><tt>E0 r0</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>LOOPNZ&nbsp;&nbsp;label</tt><br>
<tt>LOOPNE&nbsp;&nbsp;label</tt>
</dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Decrements CX by 1 (without modifying the flags) and transfers<br>
control to "label" if CX != 0 and the Zero Flag is clear.  The<br>
"label" operand must be within -128 or 127 bytes of the instruction<br>
following the loop instruction.
</p><p>
<sup>*)</sup>&nbsp;LOOPNZ/LOOPNE are different mnemonics for the same instruction
</p></div>

<h4><a name="lsl">LSL - Load Segment Limit  (286+ protected)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>LSL&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rw,rmw&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[286]</tt></td><td><tt>0F 03 mr d0 d1</tt></td><td>&nbsp;</td><td><tt>3~5</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>LSL&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dest,src</tt></dd>
<dt>Modifies flags</dt><dd>ZF</dd>
</dl>
<p>
Loads the segment limit of a selector into the destination register<br>
if the selector is valid and visible at the current privilege level.<br>
If loading is successful the Zero Flag is set, otherwise it is<br>
cleared.
</p></div>

<h4><a name="lss">LSS - Load Pointer Using SS  (386+ only)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>LSS&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rw,md&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F B2 mr d0 d1</tt></td><td>&nbsp;</td><td><tt>3~5</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>LSS&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dest,src</tt></dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Loads 32-bit pointer from memory source to destination register<br>
and SS.  The offset is placed in the destination register and the<br>
segment is placed in SS.  To use this instruction the word at the<br>
lower memory address must contain the offset and the word at the<br>
higher address must contain the segment.  This simplifies the loading<br>
of far pointers from the stack and the interrupt vector table.
</p></div>

<h4><a name="ltr">LTR - Load Task Register  (286+ privileged)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>LTR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[286]</tt></td><td><tt>0F 00 /3 d0 d1</tt></td><td>&nbsp;</td><td><tt>3~5</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>LTR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;src</tt></dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Loads the current task register with the value specified in "src".
</p></div>

<h4><a name="mov">MOV - Move Byte or Word</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>MOV&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;AL,rmb</tt></td><td><tt>A0 d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>3</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>MOV&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;AX,rmw</tt></td><td><tt>A1 d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>3</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>MOV&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;AL,ib</tt></td><td><tt>B0 i0</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>MOV&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;AH,ib</tt></td><td><tt>B4 i0</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>MOV&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;AX,iw</tt></td><td><tt>B8 i0 i1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>3</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>MOV&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;CL,ib</tt></td><td><tt>B1 i0</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>MOV&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;CH,ib</tt></td><td><tt>B5 i0</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>MOV&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;CX,iw</tt></td><td><tt>B9 i0 i1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>3</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>MOV&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DL,ib</tt></td><td><tt>B2 i0</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>MOV&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DH,ib</tt></td><td><tt>B6 i0</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>MOV&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DX,iw</tt></td><td><tt>BA i0 i1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>3</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>MOV&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;BL,ib</tt></td><td><tt>B3 i0</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>MOV&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;BH,ib</tt></td><td><tt>B7 i0</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>MOV&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;BX,iw</tt></td><td><tt>BB i0 i1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>3</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>MOV&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;SP,iw</tt></td><td><tt>BC i0 i1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>3</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>MOV&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;BP,iw</tt></td><td><tt>BD i0 i1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>3</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>MOV&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;SI,iw</tt></td><td><tt>BE i0 i1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>3</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>MOV&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DI,iw</tt></td><td><tt>BF i0 i1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>3</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>MOV&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;cr,rd&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F 22 mr</tt></td><td>&nbsp;</td><td><tt>3</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>MOV&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rd,cr&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F 20 mr</tt></td><td>&nbsp;</td><td><tt>3</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>MOV&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dr,rd&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F 23 mr</tt></td><td>&nbsp;</td><td><tt>3</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>MOV&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rd,dr&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F 21 mr</tt></td><td>&nbsp;</td><td><tt>3</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>MOV&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;tr,rd&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F 26 mr</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>MOV&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rd,tr&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F 24 mr</tt></td><td>&nbsp;</td><td><tt>3</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>MOV&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rb,rmb</tt></td><td><tt>8A mr d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>MOV&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb,rb</tt></td><td><tt>88 mr d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>MOV&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb,AL</tt></td><td><tt>A2 d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>3</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>MOV&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,AX</tt></td><td><tt>A3 d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>3</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>MOV&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb,ib</tt></td><td><tt>C6 mr d0 d1 i0</tt></td><td><tt>&nbsp;B</tt></td><td><tt>3~5</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>MOV&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,iw</tt></td><td><tt>C7 mr d0 d1 i0 i1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>4~6</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>MOV&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,rw</tt></td><td><tt>89 mr d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>MOV&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rw,rmw</tt></td><td><tt>8B mr d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>MOV&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,sr</tt></td><td><tt>8C mr d0 d1</tt></td><td>&nbsp;</td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>MOV&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sr,rmw</tt></td><td><tt>8E mr d0 d1</tt></td><td>&nbsp;</td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>MOV&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dest,src</tt></dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Copies byte or word from the source operand to the destination<br>
operand.  If the destination is SS interrupts are disabled except<br>
on early buggy 808x CPUs.  Some CPUs disable interrupts if the<br>
destination is any of the segment registers
</p></div>

<h4><a name="movs">MOVS - Move String (Byte or Word)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>MOVSB</tt></td><td><tt>A4</tt></td><td><tt>&nbsp;B</tt></td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>MOVSW</tt></td><td><tt>A5</tt></td><td><tt>&nbsp;W</tt></td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>MOVSD&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[32bit]</tt></td><td><tt>66| A5</tt></td><td><tt>&nbsp;D</tt></td><td><tt>1+1</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>MOVS&nbsp;&nbsp;&nbsp;&nbsp;dest,src</tt><br>
<tt>MOVSB</tt>
<br>
<tt>MOVSW</tt>
<br>
<tt>MOVSD&nbsp;&nbsp;(386+&nbsp;only)</tt>
</dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Copies data from addressed by DS:SI (even if operands are given) to<br>
the location ES:DI destination and updates SI and DI based on the<br>
size of the operand or instruction used.  SI and DI are incremented<br>
when the Direction Flag is cleared and decremented when the Direction<br>
Flag is Set.  Use with REP prefixes.
</p></div>

<h4><a name="movsx">MOVSX - Move with Sign Extend  (386+ only)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>MOVSX&nbsp;&nbsp;&nbsp;rw,rmb&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F BE mr d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>3~5</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>MOVSX&nbsp;&nbsp;&nbsp;rd,rmw&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F BF mr d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>3~5</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>MOVSX&nbsp;&nbsp;&nbsp;dest,src</tt></dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Copies the value of the source operand to the destination register<br>
with the sign extended.
</p></div>

<h4><a name="movzx">MOVZX - Move with Zero Extend  (386+ only)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>MOVZX&nbsp;&nbsp;&nbsp;rw,rmb&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F B6 mr d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>3~5</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>MOVZX&nbsp;&nbsp;&nbsp;rd,rmw&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F B7 mr d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>3~5</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>MOVZX&nbsp;&nbsp;&nbsp;dest,src</tt></dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Copies the value of the source operand to the destination register<br>
with the zeroes extended.
</p></div>

<h4><a name="mul">MUL - Unsigned Multiply</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>MUL&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb</tt></td><td><tt>F6 /4 d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2~4</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>MUL&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw</tt></td><td><tt>F7 /4 d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>o---szap</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>MUL&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;src</tt></dd>
<dt>Modifies flags</dt><dd>CF OF (AF,PF,SF,ZF undefined)</dd>
</dl>
<p>
Unsigned multiply of the accumulator by the source.  If "src" is<br>
a byte value, then AL is used as the other multiplicand and the<br>
result is placed in AX.  If "src" is a word value, then AX is<br>
multiplied by "src" and DX:AX receives the result.  If "src" is<br>
a double word value, then EAX is multiplied by "src" and EDX:EAX<br>
receives the result.  The 386+ uses an early out algorithm which<br>
makes multiplying any size value in EAX as fast as in the 8 or 16<br>
bit registers.
</p></div>

<h4><a name="neg">NEG - Two's Complement Negation</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>NEG&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb</tt></td><td><tt>F6 /3 d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2~4</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>NEG&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw</tt></td><td><tt>F7 /3 d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>o---szap</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>NEG&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dest</tt></dd>
<dt>Modifies flags</dt><dd>AF CF OF PF SF ZF</dd>
</dl>
<p>
Subtracts the destination from 0 and saves the 2s complement of<br>
"dest" back into "dest".
</p></div>

<h4><a name="nop">NOP - No Operation</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>NOP</tt></td><td><tt>90</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>NOP</tt></dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
This is a do nothing instruction.  It results in occupation of both<br>
space and time and is most useful for patching :-) code [segments].
</p></div>

<h4><a name="not">NOT - One's Compliment Negation (Logical NOT)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>NOT&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb</tt></td><td><tt>F6 /2 d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>NOT&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw</tt></td><td><tt>F7 /2 d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>NOT&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dest</tt></dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Inverts the bits of the "dest" operand forming the 1s complement.
</p></div>

<h4><a name="or">OR - Inclusive Logical OR</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>OR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;AL,ib</tt></td><td><tt>0C i0</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>OR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;AX,iw</tt></td><td><tt>0D i0 i1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>3</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>OR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rb,rmb</tt></td><td><tt>0A mr d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2~4</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>OR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rw,rmw</tt></td><td><tt>0B mr d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>OR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb,ib</tt></td><td><tt>80 /1 d0 d1 i0</tt></td><td><tt>NB</tt></td><td><tt>3~5</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>OR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,iw</tt></td><td><tt>81 /1 d0 d1 i0 i1</tt></td><td><tt>NW</tt></td><td><tt>4~6</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>OR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,ib</tt></td><td><tt>83 /1 d0 d1 i0</tt></td><td><tt>EW</tt></td><td><tt>3~5</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>OR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb,rb</tt></td><td><tt>08 mr d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2~4</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>OR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,rw</tt></td><td><tt>09 mr d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>o---szap</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>OR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dest,src</tt></dd>
<dt>Modifies flags</dt><dd>CF OF PF SF ZF (AF undefined)</dd>
</dl>
<p>
Logical inclusive OR of the two operands returning the result in<br>
the destination.  Any bit set in either operand will be set in the<br>
destination.
</p></div>

<h4><a name="out">OUT - Output Data to Port</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>OUT&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DX,AL</tt></td><td><tt>EE</tt></td><td><tt>&nbsp;B</tt></td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>OUT&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DX,AX</tt></td><td><tt>EF</tt></td><td><tt>&nbsp;W</tt></td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>OUT&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ib,AL</tt></td><td><tt>E6 i0</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>OUT&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ib,AX</tt></td><td><tt>E7 i0</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>OUT&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;port,accum</tt></dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Transfers byte in AL,word in AX or dword in EAX to the specified<br>
hardware port address.  If the port number is in the range of 0-255<br>
it can be specified as an immediate.  If greater than 255 then the<br>
port number must be specified in DX.  Since the PC only decodes 10<br>
bits of the port address, values over 1023 can only be decoded by<br>
third party vendor equipment and also map to the port range 0-1023.
</p></div>

<h4><a name="outs">OUTS - Output String to Port  (80188+ only)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>OUTSB&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[186]</tt></td><td><tt>6E</tt></td><td><tt>&nbsp;B</tt></td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>OUTSW&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[186]</tt></td><td><tt>6F</tt></td><td><tt>&nbsp;W</tt></td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>OUTSD&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[32bit]</tt></td><td><tt>66| 6F</tt></td><td><tt>&nbsp;D</tt></td><td><tt>1+1</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>OUTS&nbsp;&nbsp;&nbsp;&nbsp;port,src</tt><br>
<tt>OUTSB</tt>
<br>
<tt>OUTSW</tt>
<br>
<tt>OUTSD&nbsp;&nbsp;(386+&nbsp;only)</tt>
</dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Transfers a byte, word or doubleword from "src" to the hardware<br>
port specified in DX.  For instructions with no operands the "src"<br>
is located at DS:SI and SI is incremented or decremented by the<br>
size of the operand or the size dictated by the instruction format.<br>
When the Direction Flag is set SI is decremented, when clear, SI is<br>
incremented.  If the port number is in the range of 0-255 it can<br>
be specified as an immediate.  If greater than 255 then the port<br>
number must be specified in DX.  Since the PC only decodes 10 bits<br>
of the port address, values over 1023 can only be decoded by third<br>
party vendor equipment and also map to the port range 0-1023.
</p></div>

<h4><a name="pop">POP - Pop Word off Stack</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>POP&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;AX</tt></td><td><tt>58</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>POP&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;CX</tt></td><td><tt>59</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>POP&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DX</tt></td><td><tt>5A</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>POP&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;BX</tt></td><td><tt>5B</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>POP&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;SP</tt></td><td><tt>5C</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>POP&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;BP</tt></td><td><tt>5D</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>POP&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;SI</tt></td><td><tt>5E</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>POP&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DI</tt></td><td><tt>5F</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>POP&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ES</tt></td><td><tt>07</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>POP&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;SS</tt></td><td><tt>17</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>POP&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DS</tt></td><td><tt>1F</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>POP&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;FS&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F A1</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>POP&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;GS&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F A9</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>POP&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw</tt></td><td><tt>8F mr d0 d1</tt></td><td>&nbsp;</td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>POP&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dest</tt></dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Transfers word at the current stack top (SS:SP) to the destination<br>
then increments SP by two to point to the new stack top.  CS is not<br>
a valid destination.
</p></div>

<h4><a name="popa">POPA/POPAD - Pop All Registers onto Stack  (80188+ only)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>POPA&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[186]</tt></td><td><tt>61</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>POPAD&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[32bit]</tt></td><td><tt>66| 61</tt></td><td>&nbsp;</td><td><tt>1+1</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>POPA</tt><br>
<tt>POPAD&nbsp;&nbsp;(386+&nbsp;only)</tt>
</dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Pops the top 8 words off the stack into the 8 general purpose 16/32<br>
bit registers.   Registers are popped in the following order: (E)DI,<br>
(E)SI, (E)BP, (E)SP, (E)DX, (E)CX and (E)AX.  The (E)SP value popped<br>
from the stack is actually discarded.
</p></div>

<h4><a name="popf">POPF/POPFD - Pop Flags off Stack</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>POPF</tt></td><td><tt>9D</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>oditszap</tt></td></tr>
<tr><td><tt>POPFD&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[32bit]</tt></td><td><tt>66| 9D</tt></td><td>&nbsp;</td><td><tt>1+1</tt></td><td><tt>oditszap</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>POPF</tt><br>
<tt>POPFD&nbsp;&nbsp;(386+&nbsp;only)</tt>
</dd>
<dt>Modifies flags</dt><dd>all flags</dd>
</dl>
<p>
Pops word/doubleword from stack into the Flags Register and then<br>
increments SP by 2 (for POPF) or 4 (for POPFD).
</p></div>

<h4><a name="push">PUSH - Push Word onto Stack</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>PUSH&nbsp;&nbsp;&nbsp;&nbsp;AX</tt></td><td><tt>50</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>PUSH&nbsp;&nbsp;&nbsp;&nbsp;CX</tt></td><td><tt>51</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>PUSH&nbsp;&nbsp;&nbsp;&nbsp;DX</tt></td><td><tt>52</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>PUSH&nbsp;&nbsp;&nbsp;&nbsp;BX</tt></td><td><tt>53</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>PUSH&nbsp;&nbsp;&nbsp;&nbsp;SP</tt></td><td><tt>54</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>PUSH&nbsp;&nbsp;&nbsp;&nbsp;BP</tt></td><td><tt>55</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>PUSH&nbsp;&nbsp;&nbsp;&nbsp;SI</tt></td><td><tt>56</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>PUSH&nbsp;&nbsp;&nbsp;&nbsp;DI</tt></td><td><tt>57</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>PUSH&nbsp;&nbsp;&nbsp;&nbsp;ES</tt></td><td><tt>06</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>PUSH&nbsp;&nbsp;&nbsp;&nbsp;CS</tt></td><td><tt>0E</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>PUSH&nbsp;&nbsp;&nbsp;&nbsp;SS</tt></td><td><tt>16</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>PUSH&nbsp;&nbsp;&nbsp;&nbsp;DS</tt></td><td><tt>1E</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>PUSH&nbsp;&nbsp;&nbsp;&nbsp;FS&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F A0</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>PUSH&nbsp;&nbsp;&nbsp;&nbsp;GS&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F A8</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>PUSH&nbsp;&nbsp;&nbsp;&nbsp;ib&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[186]</tt></td><td><tt>6A i0</tt></td><td><tt>E</tt></td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>PUSH&nbsp;&nbsp;&nbsp;&nbsp;iw&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[186]</tt></td><td><tt>68 i0 i1</tt></td><td><tt>N</tt></td><td><tt>3</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>PUSH&nbsp;&nbsp;&nbsp;&nbsp;rmw</tt></td><td><tt>FF /6 d0 d1</tt></td><td>&nbsp;</td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>PUSH&nbsp;&nbsp;&nbsp;&nbsp;src</tt><br>
<tt>PUSH&nbsp;&nbsp;&nbsp;&nbsp;immed&nbsp;&nbsp;&nbsp;(80188+&nbsp;only)</tt>
</dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Decrements SP by the size of the operand (two or four, byte values<br>
are sign extended) and transfers one word from source to the stack<br>
top (SS:SP).
</p></div>

<h4><a name="pusha">PUSHA/PUSHAD - Push All Registers onto Stack  (80188+ only)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>PUSHA&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[186]</tt></td><td><tt>60</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>PUSHAD&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[32bit]</tt></td><td><tt>66| 60</tt></td><td>&nbsp;</td><td><tt>1+1</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>PUSHA</tt><br>
<tt>PUSHAD&nbsp;&nbsp;(386+&nbsp;only)</tt>
</dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Pushes all general purpose registers onto the stack in the following<br>
order: (E)AX, (E)CX, (E)DX, (E)BX, (E)SP, (E)BP, (E)SI, (E)DI.  The<br>
value of SP is the value before the actual push of SP.
</p></div>

<h4><a name="pushf">PUSHF/PUSHFD - Push Flags onto Stack</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>PUSHF</tt></td><td><tt>9C</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>PUSHFD&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[32bit]</tt></td><td><tt>66| 9C</tt></td><td>&nbsp;</td><td><tt>1+1</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>PUSHF</tt><br>
<tt>PUSHFD&nbsp;&nbsp;(386+&nbsp;only)</tt>
</dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Transfers the Flags Register onto the stack.  PUSHF saves a 16 bit<br>
value while PUSHFD saves a 32 bit value.
</p></div>

<h4><a name="rcl">RCL - Rotate Through Carry Left</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>RCL&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb,1</tt></td><td><tt>D0 /2 d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2~4</tt></td><td><tt>o-------</tt></td></tr>
<tr><td><tt>RCL&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb,CL</tt></td><td><tt>D2 /2 d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2~4</tt></td><td><tt>o-------</tt></td></tr>
<tr><td><tt>RCL&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb,ib&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[186]</tt></td><td><tt>C0 /2 d0 d1 i0</tt></td><td><tt>&nbsp;B</tt></td><td><tt>3~5</tt></td><td><tt>o-------</tt></td></tr>
<tr><td><tt>RCL&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,1</tt></td><td><tt>D1 /2 d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>o-------</tt></td></tr>
<tr><td><tt>RCL&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,CL</tt></td><td><tt>D3 /2 d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>o-------</tt></td></tr>
<tr><td><tt>RCL&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,ib&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[186]</tt></td><td><tt>C1 /2 d0 d1 i0</tt></td><td><tt>&nbsp;W</tt></td><td><tt>3~5</tt></td><td><tt>o-------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>RCL&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dest,count</tt></dd>
<dt>Modifies flags</dt><dd>CF OF</dd>
</dl>
<p>
Rotates the bits in the destination to the left "count" times with<br>
all data pushed out the left side re-entering on the right.  The<br>
Carry Flag holds the last bit rotated out.
</p></div>

<h4><a name="rcr">RCR - Rotate Through Carry Right</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>RCR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb,1</tt></td><td><tt>D0 /3 d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2~4</tt></td><td><tt>o-------</tt></td></tr>
<tr><td><tt>RCR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb,CL</tt></td><td><tt>D2 /3 d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2~4</tt></td><td><tt>o-------</tt></td></tr>
<tr><td><tt>RCR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb,ib&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[186]</tt></td><td><tt>C0 /3 d0 d1 i0</tt></td><td><tt>&nbsp;B</tt></td><td><tt>3~5</tt></td><td><tt>o-------</tt></td></tr>
<tr><td><tt>RCR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,1</tt></td><td><tt>D1 /3 d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>o-------</tt></td></tr>
<tr><td><tt>RCR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,CL</tt></td><td><tt>D3 /3 d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>o-------</tt></td></tr>
<tr><td><tt>RCR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,ib&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[186]</tt></td><td><tt>C1 /3 d0 d1 i0</tt></td><td><tt>&nbsp;W</tt></td><td><tt>3~5</tt></td><td><tt>o-------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>RCR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dest,count</tt></dd>
<dt>Modifies flags</dt><dd>CF OF</dd>
</dl>
<p>
Rotates the bits in the destination to the right "count" times with<br>
all data pushed out the right side re-entering on the left.  The<br>
Carry Flag holds the last bit rotated out.
</p></div>

<h4><a name="rep">REP - Repeat String Operation</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>REP</tt></td><td><tt>F3</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>-----z--</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>REP</tt></dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Repeats execution of string instructions while CX != 0.  After<br>
each string operation, CX is decremented and the Zero Flag is<br>
tested.  The combination of a repeat prefix and a segment override<br>
on CPU's before the 386 may result in errors if an interrupt occurs<br>
before CX=0.  The following code shows code that is susceptible to<br>
this and how to avoid it:<br>
<tt>again:  rep movs  byte ptr ES:[DI],ES:[SI]   ; vulnerable instr.</tt><br>
<tt>jcxz  next              ; continue if REP successful</tt><br>
<tt>loop  again             ; interrupt goofed count</tt><br>
<tt>next:</tt>
</p></div>

<h4><a name="repe">REPE/REPZ - Repeat Equal / Repeat Zero</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>REPE</tt></td><td><tt>F3</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>REPE</tt><br>
<tt>REPZ</tt>
</dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Repeats execution of string instructions while CX != 0 and the Zero<br>
Flag is set.  CX is decremented and the Zero Flag tested after<br>
each string operation.   The combination of a repeat prefix and a<br>
segment override on processors other than the 386 may result in<br>
errors if an interrupt occurs before CX=0.
</p><p>
<sup>*)</sup>&nbsp;REPE/REPZ are different mnemonics for the same instruction
</p></div>

<h4><a name="repne">REPNE/REPNZ - Repeat Not Equal / Repeat Not Zero</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>REPNE</tt></td><td><tt>F2</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>-----z--</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>REPNE</tt><br>
<tt>REPNZ</tt>
</dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Repeats execution of string instructions while CX != 0 and the Zero<br>
Flag is clear.   CX is decremented and the Zero Flag tested after<br>
each string operation.   The combination of a repeat prefix and a<br>
segment override on processors other than the 386 may result in<br>
errors if an interrupt occurs before CX=0.
</p><p>
<sup>*)</sup>&nbsp;REPNE/REPNZ are different mnemonics for the same instruction
</p></div>

<h4><a name="ret">RET/RETF - Return From Procedure</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>RET</tt></td><td><tt>C3</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>RET&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;iw</tt></td><td><tt>C2 i0 i1</tt></td><td>&nbsp;</td><td><tt>3</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>RETF</tt></td><td><tt>CB</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>RETF&nbsp;&nbsp;&nbsp;&nbsp;iw</tt></td><td><tt>CA i0 i1</tt></td><td>&nbsp;</td><td><tt>3</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>RET&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;nBytes</tt><br>
<tt>RETF&nbsp;&nbsp;&nbsp;&nbsp;nBytes</tt>
<br>
<tt>RETN&nbsp;&nbsp;&nbsp;&nbsp;nBytes</tt>
</dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Transfers control from a procedure back to the instruction address<br>
saved on the stack.  "n bytes" is an optional number of bytes to<br>
release.  Far returns pop the IP followed by the CS, while near<br>
returns pop only the IP register.
</p></div>

<h4><a name="rol">ROL - Rotate Left</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>ROL&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb,1</tt></td><td><tt>D0 /0 d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2~4</tt></td><td><tt>o-------</tt></td></tr>
<tr><td><tt>ROL&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb,CL</tt></td><td><tt>D2 /0 d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2~4</tt></td><td><tt>o-------</tt></td></tr>
<tr><td><tt>ROL&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb,ib&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[186]</tt></td><td><tt>C0 /0 d0 d1 i0</tt></td><td><tt>&nbsp;B</tt></td><td><tt>3~5</tt></td><td><tt>o-------</tt></td></tr>
<tr><td><tt>ROL&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,1</tt></td><td><tt>D1 /0 d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>o-------</tt></td></tr>
<tr><td><tt>ROL&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,CL</tt></td><td><tt>D3 /0 d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>o-------</tt></td></tr>
<tr><td><tt>ROL&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,ib&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[186]</tt></td><td><tt>C1 /0 d0 d1 i0</tt></td><td><tt>&nbsp;W</tt></td><td><tt>3~5</tt></td><td><tt>o-------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>ROL&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dest,count</tt></dd>
<dt>Modifies flags</dt><dd>CF OF</dd>
</dl>
<p>
Rotates the bits in the destination to the left "count" times with<br>
all data pushed out the left side re-entering on the right.  The<br>
Carry Flag will contain the value of the last bit rotated out.
</p></div>

<h4><a name="ror">ROR - Rotate Right</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>ROR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb,1</tt></td><td><tt>D0 /1 d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2~4</tt></td><td><tt>o-------</tt></td></tr>
<tr><td><tt>ROR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb,CL</tt></td><td><tt>D2 /1 d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2~4</tt></td><td><tt>o-------</tt></td></tr>
<tr><td><tt>ROR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb,ib&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[186]</tt></td><td><tt>C0 /1 d0 d1 i0</tt></td><td><tt>&nbsp;B</tt></td><td><tt>3~5</tt></td><td><tt>o-------</tt></td></tr>
<tr><td><tt>ROR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,1</tt></td><td><tt>D1 /1 d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>o-------</tt></td></tr>
<tr><td><tt>ROR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,CL</tt></td><td><tt>D3 /1 d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>o-------</tt></td></tr>
<tr><td><tt>ROR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,ib&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[186]</tt></td><td><tt>C1 /1 d0 d1 i0</tt></td><td><tt>&nbsp;W</tt></td><td><tt>3~5</tt></td><td><tt>o-------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>ROR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dest,count</tt></dd>
<dt>Modifies flags</dt><dd>CF OF</dd>
</dl>
<p>
Rotates the bits in the destination to the right "count" times with<br>
all data pushed out the right side re-entering on the left.  The<br>
Carry Flag will contain the value of the last bit rotated out.
</p></div>

<h4><a name="sahf">SAHF - Store AH Register into FLAGS</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>SAHF</tt></td><td><tt>9E</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>----szap</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>SAHF</tt></dd>
<dt>Modifies flags</dt><dd>AF CF PF SF ZF</dd>
</dl>
<p>
Transfers bits 0-7 of AH into the Flags Register.  This includes AF, CF, PF, SF and ZF.
</p></div>

<h4><a name="sal">SAL/SHL - Shift Arithmetic Left / Shift Logical Left</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>SAL&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb,1</tt></td><td><tt>D0 /4 d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2~4</tt></td><td><tt>o-------</tt></td></tr>
<tr><td><tt>SAL&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb,CL</tt></td><td><tt>D2 /4 d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2~4</tt></td><td><tt>o-------</tt></td></tr>
<tr><td><tt>SAL&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb,ib&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[186]</tt></td><td><tt>C0 /4 d0 d1 i0</tt></td><td><tt>&nbsp;B</tt></td><td><tt>3~5</tt></td><td><tt>o-------</tt></td></tr>
<tr><td><tt>SAL&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,1</tt></td><td><tt>D1 /4 d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>o-------</tt></td></tr>
<tr><td><tt>SAL&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,CL</tt></td><td><tt>D3 /4 d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>o-------</tt></td></tr>
<tr><td><tt>SAL&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,ib&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[186]</tt></td><td><tt>C1 /4 d0 d1 i0</tt></td><td><tt>&nbsp;W</tt></td><td><tt>3~5</tt></td><td><tt>o-------</tt></td></tr>
<tr><td><tt>SHL&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb,1</tt></td><td><tt>D0 /4 d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2~4</tt></td><td><tt>o-------</tt></td></tr>
<tr><td><tt>SHL&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb,CL</tt></td><td><tt>D2 /4 d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2~4</tt></td><td><tt>o-------</tt></td></tr>
<tr><td><tt>SHL&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb,ib&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[186]</tt></td><td><tt>C0 /4 d0 d1 i0</tt></td><td><tt>&nbsp;B</tt></td><td><tt>3~5</tt></td><td><tt>o-------</tt></td></tr>
<tr><td><tt>SHL&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,1</tt></td><td><tt>D1 /4 d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>o-------</tt></td></tr>
<tr><td><tt>SHL&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,CL</tt></td><td><tt>D3 /4 d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>o-------</tt></td></tr>
<tr><td><tt>SHL&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,ib&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[186]</tt></td><td><tt>C1 /4 d0 d1 i0</tt></td><td><tt>&nbsp;W</tt></td><td><tt>3~5</tt></td><td><tt>o-------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>SAL&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dest,count</tt><br>
<tt>SHL&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dest,count</tt>
</dd>
<dt>Modifies flags</dt><dd>CF OF PF SF ZF (AF undefined)</dd>
</dl>
<p>
Shifts the destination left by "count" bits with zeroes shifted<br>
in on right.  The Carry Flag contains the last bit shifted out.
</p></div>

<h4><a name="sar">SAR - Shift Arithmetic Right</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>SAR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb,CL</tt></td><td><tt>D2 /7 d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2~4</tt></td><td><tt>o-------</tt></td></tr>
<tr><td><tt>SAR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb,ib&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[186]</tt></td><td><tt>C0 /7 d0 d1 i0</tt></td><td><tt>&nbsp;B</tt></td><td><tt>3~5</tt></td><td><tt>o-------</tt></td></tr>
<tr><td><tt>SAR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,1</tt></td><td><tt>D1 /7 d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>o-------</tt></td></tr>
<tr><td><tt>SAR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,CL</tt></td><td><tt>D3 /7 d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>o-------</tt></td></tr>
<tr><td><tt>SAR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,ib&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[186]</tt></td><td><tt>C1 /7 d0 d1 i0</tt></td><td><tt>&nbsp;W</tt></td><td><tt>3~5</tt></td><td><tt>o-------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>SAR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dest,count</tt></dd>
<dt>Modifies flags</dt><dd>CF OF PF SF ZF (AF undefined)</dd>
</dl>
<p>
Shifts the destination right by "count" bits with the current sign<br>
bit replicated in the leftmost bit.  The Carry Flag contains the<br>
last bit shifted out.
</p></div>

<h4><a name="sbb">SBB - Subtract with Borrow</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>SBB&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;AL,ib</tt></td><td><tt>1C i0</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>SBB&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;AX,iw</tt></td><td><tt>1D i0 i1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>3</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>SBB&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rb,rmb</tt></td><td><tt>1A mr d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2~4</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>SBB&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rw,rmw</tt></td><td><tt>1B mr d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>SBB&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb,ib</tt></td><td><tt>80 /3 d0 d1 i0</tt></td><td><tt>NB</tt></td><td><tt>3~5</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>SBB&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,iw</tt></td><td><tt>81 /3 d0 d1 i0 i1</tt></td><td><tt>NW</tt></td><td><tt>4~6</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>SBB&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,ib</tt></td><td><tt>83 /3 d0 d1 i0</tt></td><td><tt>EW</tt></td><td><tt>3~5</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>SBB&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb,rb</tt></td><td><tt>18 mr d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2~4</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>SBB&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,rw</tt></td><td><tt>19 mr d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>o---szap</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>SBB&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dest,src</tt></dd>
<dt>Modifies flags</dt><dd>AF CF OF PF SF ZF</dd>
</dl>
<p>
Subtracts the source from the destination, and subtracts 1 extra if<br>
the Carry Flag is set.   Results are returned in "dest".
</p></div>

<h4><a name="scas">SCAS - Scan String (Byte, Word or Doubleword)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>SCASB</tt></td><td><tt>AE</tt></td><td><tt>&nbsp;B</tt></td><td><tt>1</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>SCASW</tt></td><td><tt>AF</tt></td><td><tt>&nbsp;W</tt></td><td><tt>1</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>SCASD&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[32bit]</tt></td><td><tt>66| AF</tt></td><td><tt>&nbsp;D</tt></td><td><tt>1+1</tt></td><td><tt>o---szap</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>SCAS&nbsp;&nbsp;&nbsp;&nbsp;string</tt><br>
<tt>SCASB</tt>
<br>
<tt>SCASW</tt>
<br>
<tt>SCASD&nbsp;&nbsp;&nbsp;(386+&nbsp;only)</tt>
</dd>
<dt>Modifies flags</dt><dd>AF CF OF PF SF ZF</dd>
</dl>
<p>
Compares value at ES:DI (even if operand is specified) from the<br>
accumulator and sets the flags similar to a subtraction.  DI is<br>
incremented/decremented based on the instruction format (or<br>
operand size) and the state of the Direction Flag.  Use with REP<br>
prefixes.
</p></div>

<h4><a name="setae">SETAE/SETNB - Set if Above or Equal / Set if Not Below  (unsigned, 386+ only)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>SETAE&nbsp;&nbsp;&nbsp;rmb&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F 93 mr d0 d1</tt></td><td>&nbsp;</td><td><tt>3~5</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>SETAE&nbsp;&nbsp;&nbsp;dest</tt><br>
<tt>SETNB&nbsp;&nbsp;&nbsp;dest</tt>
</dd>
<dt>Modifies flags</dt><dd>none</dd>
</dl>
<p>
Sets the byte in the operand to 1 if the Carry Flag is clear<br>
otherwise sets the operand to 0.
<br>
</p><p>
<sup>*)</sup>&nbsp;SETAE/SETNB are different mnemonics for the same instruction
</p></div>

<h4><a name="setb">SETB/SETNAE - Set if Below / Set if Not Above or Equal  (unsigned, 386+ only)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>SETB&nbsp;&nbsp;&nbsp;&nbsp;rmb&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F 92 mr d0 d1</tt></td><td>&nbsp;</td><td><tt>3~5</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>SETB&nbsp;&nbsp;&nbsp;&nbsp;dest</tt><br>
<tt>SETNAE&nbsp;&nbsp;dest</tt>
</dd>
<dt>Modifies flags</dt><dd>none</dd>
</dl>
<p>
Sets the byte in the operand to 1 if the Carry Flag is set<br>
otherwise sets the operand to 0.
</p><p>
<sup>*)</sup>&nbsp;SETB/SETAE are different mnemonics for the same instruction
</p></div>

<h4><a name="setbe">SETBE/SETNA - Set if Below or Equal / Set if Not Above  (unsigned, 386+ only)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>SETBE&nbsp;&nbsp;&nbsp;rmb&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F 96 mr d0 d1</tt></td><td>&nbsp;</td><td><tt>3~5</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>SETBE&nbsp;&nbsp;&nbsp;dest</tt><br>
<tt>SETNA&nbsp;&nbsp;&nbsp;dest</tt>
</dd>
<dt>Modifies flags</dt><dd>none</dd>
</dl>
<p>
Sets the byte in the operand to 1 if the Carry Flag or the Zero<br>
Flag is set, otherwise sets the operand to 0.
</p><p>
<sup>*)</sup>&nbsp;SETBE/SETNA are different mnemonics for the same instruction
</p></div>

<h4><a name="sete">SETE/SETZ - Set if Equal / Set if Zero  (386+ only)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>SETZ&nbsp;&nbsp;&nbsp;&nbsp;rmb&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F 94 mr d0 d1</tt></td><td>&nbsp;</td><td><tt>3~5</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>SETE&nbsp;&nbsp;&nbsp;&nbsp;dest</tt><br>
<tt>SETZ&nbsp;&nbsp;&nbsp;&nbsp;dest</tt>
</dd>
<dt>Modifies flags</dt><dd>none</dd>
</dl>
<p>
Sets the byte in the operand to 1 if the Zero Flag is set,<br>
otherwise sets the operand to 0.
</p><p>
<sup>*)</sup>&nbsp;SETE/SETZ are different mnemonics for the same instruction
</p></div>

<h4><a name="setne">SETNE/SETNZ - Set if Not Equal / Set if Not Zero  (386+ only)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>SETNE&nbsp;&nbsp;&nbsp;rmb&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F 95 mr d0 d1</tt></td><td>&nbsp;</td><td><tt>3~5</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>SETNE&nbsp;&nbsp;&nbsp;dest</tt><br>
<tt>SETNZ&nbsp;&nbsp;&nbsp;dest</tt>
</dd>
<dt>Modifies flags</dt><dd>none</dd>
</dl>
<p>
Sets the byte in the operand to 1 if the Zero Flag is clear,<br>
otherwise sets the operand to 0.
</p><p>
<sup>*)</sup>&nbsp;SETNE/SETNZ are different mnemonics for the same instruction
</p></div>

<h4><a name="setl">SETL/SETNGE - Set if Less / Set if Not Greater or Equal  (signed, 386+ only)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>SETL&nbsp;&nbsp;&nbsp;&nbsp;rmb&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F 9C mr d0 d1</tt></td><td>&nbsp;</td><td><tt>3~5</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>SETL&nbsp;&nbsp;&nbsp;&nbsp;dest</tt><br>
<tt>SETNGE&nbsp;&nbsp;dest</tt>
</dd>
<dt>Modifies flags</dt><dd>none</dd>
</dl>
<p>
Sets the byte in the operand to 1 if the Sign Flag is not equal<br>
to the Overflow Flag, otherwise sets the operand to 0.
</p><p>
<sup>*)</sup>&nbsp;SETL/SETNGE are different mnemonics for the same instruction
</p></div>

<h4><a name="setge">SETGE/SETNL - Set if Greater or Equal / Set if Not Less  (signed, 386+ only)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>SETGE&nbsp;&nbsp;&nbsp;rmb&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F 9D mr d0 d1</tt></td><td>&nbsp;</td><td><tt>3~5</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>SETGE&nbsp;&nbsp;&nbsp;dest</tt><br>
<tt>SETNL&nbsp;&nbsp;&nbsp;dest</tt>
</dd>
<dt>Modifies flags</dt><dd>none</dd>
</dl>
<p>
Sets the byte in the operand to 1 if the Sign Flag equals the<br>
Overflow Flag, otherwise sets the operand to 0.
</p><p>
<sup>*)</sup>&nbsp;SETGE/SETNL are different mnemonics for the same instruction
</p></div>

<h4><a name="setle">SETLE/SETNG - Set if Less or Equal / Set if Not greater or Equal  (signed, 386+ only)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>SETLE&nbsp;&nbsp;&nbsp;rmb&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F 9E mr d0 d1</tt></td><td>&nbsp;</td><td><tt>3~5</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>SETLE&nbsp;&nbsp;&nbsp;dest</tt><br>
<tt>SETNG&nbsp;&nbsp;&nbsp;dest</tt>
</dd>
<dt>Modifies flags</dt><dd>none</dd>
</dl>
<p>
Sets the byte in the operand to 1 if the Zero Flag is set or the<br>
Sign Flag is not equal to the Overflow Flag,  otherwise sets the<br>
operand to 0.
</p><p>
<sup>*)</sup>&nbsp;SETLE/SETNG are different mnemonics for the same instruction
</p></div>

<h4><a name="setg">SETG/SETNLE - Set if Greater / Set if Not Less or Equal  (signed, 386+ only)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>SETG&nbsp;&nbsp;&nbsp;&nbsp;rmb&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F 9F mr d0 d1</tt></td><td>&nbsp;</td><td><tt>3~5</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>SETG&nbsp;&nbsp;&nbsp;&nbsp;dest</tt><br>
<tt>SETNLE&nbsp;&nbsp;dest</tt>
</dd>
<dt>Modifies flags</dt><dd>none</dd>
</dl>
<p>
Sets the byte in the operand to 1 if the Zero Flag is clear or the<br>
Sign Flag equals to the Overflow Flag,  otherwise sets the operand to 0.
</p><p>
<sup>*)</sup>&nbsp;SETG/SETNLE are different mnemonics for the same instruction
</p></div>

<h4><a name="sets">SETS - Set if Signed  (386+ only)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>SETS&nbsp;&nbsp;&nbsp;&nbsp;rmb&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F 98 mr d0 d1</tt></td><td>&nbsp;</td><td><tt>3~5</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>SETS&nbsp;&nbsp;&nbsp;&nbsp;dest</tt></dd>
<dt>Modifies flags</dt><dd>none</dd>
</dl>
<p>
Sets the byte in the operand to 1 if the Sign Flag is set, otherwise<br>
sets the operand to 0.
</p></div>

<h4><a name="setns">SETNS - Set if Not Signed  (386+ only)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>SETNS&nbsp;&nbsp;&nbsp;rmb&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F 99 mr d0 d1</tt></td><td>&nbsp;</td><td><tt>3~5</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>SETNS&nbsp;&nbsp;&nbsp;dest</tt></dd>
<dt>Modifies flags</dt><dd>none</dd>
</dl>
<p>
Sets the byte in the operand to 1 if the Sign Flag is clear,<br>
otherwise sets the operand to 0.
</p></div>

<h4><a name="setc">SETC - Set if Carry  (386+ only)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>SETC&nbsp;&nbsp;&nbsp;&nbsp;rmb&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F 92 mr d0 d1</tt></td><td>&nbsp;</td><td><tt>3~5</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>SETC&nbsp;&nbsp;&nbsp;&nbsp;dest</tt></dd>
<dt>Modifies flags</dt><dd>none</dd>
</dl>
<p>
Sets the byte in the operand to 1 if the Carry Flag is set,<br>
otherwise sets the operand to 0.
</p></div>

<h4><a name="setnc">SETNC - Set if Not Carry  (386+ only)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>SETNC&nbsp;&nbsp;&nbsp;rmb&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F 93 mr d0 d1</tt></td><td>&nbsp;</td><td><tt>3~5</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>SETNC&nbsp;&nbsp;&nbsp;dest</tt></dd>
<dt>Modifies flags</dt><dd>none</dd>
</dl>
<p>
Sets the byte in the operand to 1 if the Carry Flag is clear,<br>
otherwise sets the operand to 0.
</p></div>

<h4><a name="seto">SETO - Set if Overflow  (386+ only)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>SETO&nbsp;&nbsp;&nbsp;&nbsp;rmb&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F 90 mr d0 d1</tt></td><td>&nbsp;</td><td><tt>3~5</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>SETO&nbsp;&nbsp;&nbsp;&nbsp;dest</tt></dd>
<dt>Modifies flags</dt><dd>none</dd>
</dl>
<p>
Sets the byte in the operand to 1 if the Overflow Flag is set,<br>
otherwise sets the operand to 0.
</p></div>

<h4><a name="setno">SETNO - Set if Not Overflow  (386+ only)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>SETNO&nbsp;&nbsp;&nbsp;rmb&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F 91 mr d0 d1</tt></td><td>&nbsp;</td><td><tt>3~5</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>SETNO&nbsp;&nbsp;&nbsp;dest</tt></dd>
<dt>Modifies flags</dt><dd>none</dd>
</dl>
<p>
Sets the byte in the operand to 1 if the Overflow Flag is clear,<br>
otherwise sets the operand to 0.
<br>
</p></div>

<h4><a name="setp">SETP/SETPE - Set if Parity / Set if Parity Even  (386+ only)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>SETP&nbsp;&nbsp;&nbsp;&nbsp;rmb&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F 9A mr d0 d1</tt></td><td>&nbsp;</td><td><tt>3~5</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>SETP&nbsp;&nbsp;&nbsp;&nbsp;dest</tt><br>
<tt>SETPE&nbsp;&nbsp;&nbsp;dest</tt>
</dd>
<dt>Modifies flags</dt><dd>none</dd>
</dl>
<p>
Sets the byte in the operand to 1 if the Parity Flag is set,<br>
otherwise sets the operand to 0.
</p><p>
<sup>*)</sup>&nbsp;SETP/SETE are different mnemonics for the same instruction
</p></div>

<h4><a name="setnp">SETNP/SETPO - Set if No Parity / Set if Parity Odd  (386+ only)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>SETNP&nbsp;&nbsp;&nbsp;rmb&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F 9B mr d0 d1</tt></td><td>&nbsp;</td><td><tt>3~5</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>SETNP&nbsp;&nbsp;&nbsp;dest</tt><br>
<tt>SETPO&nbsp;&nbsp;&nbsp;dest</tt>
</dd>
<dt>Modifies flags</dt><dd>none</dd>
</dl>
<p>
Sets the byte in the operand to 1 if the Parity Flag is clear,<br>
otherwise sets the operand to 0.
</p><p>
<sup>*)</sup>&nbsp;SETNP/SETPO are different mnemonics for the same instruction
</p></div>

<h4><a name="sgdt">SGDT - Store Global Descriptor Table  (286+ privileged)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>SGDT&nbsp;&nbsp;&nbsp;&nbsp;m6&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[286]</tt></td><td><tt>0F 01 /0 d0 d1</tt></td><td>&nbsp;</td><td><tt>3~5</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>SGDT&nbsp;&nbsp;&nbsp;&nbsp;dest</tt></dd>
<dt>Modifies flags</dt><dd>none</dd>
</dl>
<p>
Stores the Global Descriptor Table (GDT) Register into the<br>
specified operand.
</p></div>

<h4><a name="sidt">SIDT - Store Interrupt Descriptor Table  (286+ privileged)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>SIDT&nbsp;&nbsp;&nbsp;&nbsp;m6&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[286]</tt></td><td><tt>0F 01 /1 d0 d1</tt></td><td>&nbsp;</td><td><tt>3~5</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>SIDT&nbsp;&nbsp;&nbsp;&nbsp;dest</tt></dd>
<dt>Modifies flags</dt><dd>none</dd>
</dl>
<p>
Stores the Interrupt Descriptor Table (IDT) Register into the<br>
specified operand.
</p></div>

<h4><a name="shr">SHR - Shift Logical Right</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>SHR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb,1</tt></td><td><tt>D0 /5 d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2~4</tt></td><td><tt>o-------</tt></td></tr>
<tr><td><tt>SHR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb,CL</tt></td><td><tt>D2 /5 d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2~4</tt></td><td><tt>o-------</tt></td></tr>
<tr><td><tt>SHR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb,ib&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[186]</tt></td><td><tt>C0 /5 d0 d1 i0</tt></td><td><tt>&nbsp;B</tt></td><td><tt>3~5</tt></td><td><tt>o-------</tt></td></tr>
<tr><td><tt>SHR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,1</tt></td><td><tt>D1 /5 d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>o-------</tt></td></tr>
<tr><td><tt>SHR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,CL</tt></td><td><tt>D3 /5 d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>o-------</tt></td></tr>
<tr><td><tt>SHR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,ib&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[186]</tt></td><td><tt>C1 /5 d0 d1 i0</tt></td><td><tt>&nbsp;W</tt></td><td><tt>3~5</tt></td><td><tt>o-------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>SHR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dest,count</tt></dd>
<dt>Modifies flags</dt><dd>CF OF PF SF ZF (AF undefined)</dd>
</dl>
<p>
Shifts the destination right by "count" bits with zeroes shifted<br>
in on the left.  The Carry Flag contains the last bit shifted out.
</p></div>

<h4><a name="shld">SHLD/SHRD - Double Precision Shift  (386+ only)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>SHLD&nbsp;&nbsp;&nbsp;&nbsp;rmw,rw,CL&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F A5 mr d0 d1</tt></td><td>&nbsp;</td><td><tt>3~5</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>SHLD&nbsp;&nbsp;&nbsp;&nbsp;rmw,rw,ib&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F A4 mr d0 d1 i0</tt></td><td>&nbsp;</td><td><tt>4~6</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>SHRD&nbsp;&nbsp;&nbsp;&nbsp;rmw,rw,CL&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F AD mr d0 d1</tt></td><td>&nbsp;</td><td><tt>3~5</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>SHRD&nbsp;&nbsp;&nbsp;&nbsp;rmw,rw,ib&nbsp;&nbsp;&nbsp;[386]</tt></td><td><tt>0F AC mr d0 d1 i0</tt></td><td>&nbsp;</td><td><tt>4~6</tt></td><td><tt>o---szap</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>SHLD&nbsp;&nbsp;&nbsp;&nbsp;dest,src,count</tt><br>
<tt>SHRD&nbsp;&nbsp;&nbsp;&nbsp;dest,src,count</tt>
</dd>
<dt>Modifies flags</dt><dd>CF PF SF ZF (OF,AF undefined)</dd>
</dl>
<p>
SHLD shifts "dest" to the left "count" times and the bit positions<br>
opened are filled with the most significant bits of "src".  SHRD<br>
shifts "dest" to the right "count" times and the bit positions<br>
opened are filled with the least significant bits of the second<br>
operand.  Only the 5 lower bits of "count" are used.
</p></div>

<h4><a name="sldt">SLDT - Store Local Descriptor Table  (286+ privileged)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>SLDT&nbsp;&nbsp;&nbsp;&nbsp;mw&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[286]</tt></td><td><tt>0F 00 /0 d0 d1</tt></td><td>&nbsp;</td><td><tt>3~5</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>SLDT&nbsp;&nbsp;&nbsp;&nbsp;dest</tt></dd>
<dt>Modifies flags</dt><dd>none</dd>
</dl>
<p>
Stores the Local Descriptor Table (LDT) Register into the<br>
specified operand.
</p></div>

<h4><a name="smsw">SMSW - Store Machine Status Word  (286+ privileged)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>SMSW&nbsp;&nbsp;&nbsp;&nbsp;rmw&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[286]</tt></td><td><tt>0F 01 /4 d0 d1</tt></td><td>&nbsp;</td><td><tt>3~5</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>SMSW&nbsp;&nbsp;&nbsp;&nbsp;dest</tt></dd>
<dt>Modifies flags</dt><dd>none</dd>
</dl>
<p>
Store Machine Status Word (MSW) into "dest".
</p></div>

<h4><a name="stc">STC - Set Carry</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>STC</tt></td><td><tt>F9</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>STC</tt></dd>
<dt>Modifies flags</dt><dd>CF</dd>
</dl>
<p>
Sets the Carry Flag to 1.
</p></div>

<h4><a name="std">STD - Set Direction Flag</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>STD</tt></td><td><tt>FD</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>-1------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>STD</tt></dd>
<dt>Modifies flags</dt><dd>DF</dd>
</dl>
<p>
Sets the Direction Flag to 1 causing string instructions to<br>
auto-decrement SI and DI instead of auto-increment.
</p></div>

<h4><a name="sti">STI - Set Interrupt Flag (Enable Interrupts)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>STI</tt></td><td><tt>FB</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--1-----</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>STI</tt></dd>
<dt>Modifies flags</dt><dd>IF</dd>
</dl>
<p>
Sets the Interrupt Flag to 1, enabling recognition of all CPU hardware interrupts.
</p></div>

<h4><a name="stos">STOS - Store String (Byte, Word or Doubleword)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>STOSB</tt></td><td><tt>AA</tt></td><td><tt>&nbsp;B</tt></td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>STOSW</tt></td><td><tt>AB</tt></td><td><tt>&nbsp;W</tt></td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>STOSD&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[32bit]</tt></td><td><tt>66| AB</tt></td><td><tt>&nbsp;D</tt></td><td><tt>1+1</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>STOS&nbsp;&nbsp;&nbsp;&nbsp;dest</tt><br>
<tt>STOSB</tt>
<br>
<tt>STOSW</tt>
<br>
<tt>STOSD&nbsp;&nbsp;&nbsp;(386+&nbsp;only)</tt>
</dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Stores value in accumulator to location at ES:(E)DI (even if operand<br>
is given). (E)DI is incremented/decremented based on the size of<br>
the operand (or instruction format) and the state of the Direction<br>
Flag.   Use with REP prefixes.
</p></div>

<h4><a name="str">STR - Store Task Register  (286+ privileged)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>STR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[286]</tt></td><td><tt>0F 01 /1 d0 d1</tt></td><td>&nbsp;</td><td><tt>3~5</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>STR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dest</tt></dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Stores the current Task Register to the specified operand.
</p></div>

<h4><a name="sub">SUB - Subtract</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>SUB&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;AL,ib</tt></td><td><tt>2C i0</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>SUB&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;AX,iw</tt></td><td><tt>2D i0 i1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>3</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>SUB&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rb,rmb</tt></td><td><tt>2A mr d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2~4</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>SUB&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rw,rmw</tt></td><td><tt>2B mr d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>SUB&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb,ib</tt></td><td><tt>80 /5 d0 d1 i0</tt></td><td><tt>NB</tt></td><td><tt>3~5</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>SUB&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,iw</tt></td><td><tt>81 /5 d0 d1 i0 i1</tt></td><td><tt>NW</tt></td><td><tt>4~6</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>SUB&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,ib</tt></td><td><tt>83 /5 d0 d1 i0</tt></td><td><tt>EW</tt></td><td><tt>3~5</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>SUB&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb,rb</tt></td><td><tt>28 mr d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2~4</tt></td><td><tt>o---szap</tt></td></tr>
<tr><td><tt>SUB&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,rw</tt></td><td><tt>29 mr d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>o---szap</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>SUB&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dest,src</tt></dd>
<dt>Modifies flags</dt><dd>AF CF OF PF SF ZF</dd>
</dl>
<p>
The source is subtracted from the destination and the result is<br>
stored in the destination.
</p></div>

<h4><a name="test">TEST - Test For Bit Pattern</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>TEST&nbsp;&nbsp;&nbsp;&nbsp;AL,ib</tt></td><td><tt>A8 i0</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2</tt></td><td><tt>0---szap</tt></td></tr>
<tr><td><tt>TEST&nbsp;&nbsp;&nbsp;&nbsp;AX,iw</tt></td><td><tt>A9 i0 i1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>3</tt></td><td><tt>0---szap</tt></td></tr>
<tr><td><tt>TEST&nbsp;&nbsp;&nbsp;&nbsp;rmb,ib</tt></td><td><tt>F6 /0 d0 d1 i0</tt></td><td><tt>&nbsp;B</tt></td><td><tt>3~5</tt></td><td><tt>0---szap</tt></td></tr>
<tr><td><tt>TEST&nbsp;&nbsp;&nbsp;&nbsp;rmw,iw</tt></td><td><tt>F7 /0 d0 d1 i0 i1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>4~6</tt></td><td><tt>0---szap</tt></td></tr>
<tr><td><tt>TEST&nbsp;&nbsp;&nbsp;&nbsp;rmb,rmb</tt></td><td><tt>84 mr d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2~4</tt></td><td><tt>0---szap</tt></td></tr>
<tr><td><tt>TEST&nbsp;&nbsp;&nbsp;&nbsp;rmw,rmw</tt></td><td><tt>85 mr d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>0---szap</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>TEST&nbsp;&nbsp;&nbsp;&nbsp;dest,src</tt></dd>
<dt>Modifies flags</dt><dd>CF OF PF SF ZF (AF undefined)</dd>
</dl>
<p>
Performs a logical AND of the two operands updating the flags<br>
register without saving the result.
</p></div>

<h4><a name="verr">VERR - Verify Read  (286+ protected)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>VERR&nbsp;&nbsp;&nbsp;&nbsp;rmw&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[286]</tt></td><td><tt>0F 00 /4 d0 d1</tt></td><td>&nbsp;</td><td><tt>3~5</tt></td><td><tt>-----z--</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>VERR&nbsp;&nbsp;&nbsp;&nbsp;src</tt></dd>
<dt>Modifies flags</dt><dd>ZF</dd>
</dl>
<p>
Verifies the specified segment selector is valid and is readable<br>
at the current privilege level.  If the segment is readable,<br>
the Zero Flag is set, otherwise it is cleared.
</p></div>

<h4><a name="verw">VERW - Verify Write  (286+ protected)</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>VERW&nbsp;&nbsp;&nbsp;&nbsp;rmw&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[286]</tt></td><td><tt>0F 00 /5 d0 d1</tt></td><td>&nbsp;</td><td><tt>3~5</tt></td><td><tt>-----z--</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>VERW&nbsp;&nbsp;&nbsp;&nbsp;src</tt></dd>
<dt>Modifies flags</dt><dd>ZF</dd>
</dl>
<p>
Verifies the specified segment selector is valid and is ratable<br>
at the current privilege level.  If the segment is writable,<br>
the Zero Flag is set, otherwise it is cleared.
</p></div>

<h4><a name="wait">WAIT/FWAIT - Event Wait</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>WAIT</tt></td><td><tt>9B</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>WAIT</tt><br>
<tt>FWAIT</tt>
</dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
CPU enters wait state until the coprocessor signals it has finished<br>
it's operation.  This instruction is used to prevent the CPU from<br>
accessing memory that may be temporarily in use by the coprocessor.<br>
WAIT and FWAIT are identical.
</p></div>

<h4><a name="wbinvd">WBINVD - Write-Back and Invalidate Cache</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>WBINVD&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[486]</tt></td><td><tt>0F 09</tt></td><td>&nbsp;</td><td><tt>2</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>WBINVD</tt></dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Flushes internal cache, then signals the external cache to write<br>
back current data followed by a signal to flush the external cache.
</p></div>

<h4><a name="xchg">XCHG - Exchange</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>XCHG&nbsp;&nbsp;&nbsp;&nbsp;AX,CX</tt></td><td><tt>91</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>XCHG&nbsp;&nbsp;&nbsp;&nbsp;AX,DX</tt></td><td><tt>92</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>XCHG&nbsp;&nbsp;&nbsp;&nbsp;AX,BX</tt></td><td><tt>93</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>XCHG&nbsp;&nbsp;&nbsp;&nbsp;AX,SP</tt></td><td><tt>94</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>XCHG&nbsp;&nbsp;&nbsp;&nbsp;AX,BP</tt></td><td><tt>95</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>XCHG&nbsp;&nbsp;&nbsp;&nbsp;AX,SI</tt></td><td><tt>96</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>XCHG&nbsp;&nbsp;&nbsp;&nbsp;AX,DI</tt></td><td><tt>97</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>XCHG&nbsp;&nbsp;&nbsp;&nbsp;rb,rmb</tt></td><td><tt>86 mr d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>XCHG&nbsp;&nbsp;&nbsp;&nbsp;rmb,rb</tt></td><td><tt>86 mr d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>XCHG&nbsp;&nbsp;&nbsp;&nbsp;rmw,rw</tt></td><td><tt>87 mr d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
<tr><td><tt>XCHG&nbsp;&nbsp;&nbsp;&nbsp;rw,rmw</tt></td><td><tt>87 mr d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>XCHG&nbsp;&nbsp;&nbsp;&nbsp;dest,src</tt></dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Exchanges contents of source and destination.
</p></div>

<h4><a name="xlat">XLAT/XLATB - Translate</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>XLAT</tt></td><td><tt>D7</tt></td><td>&nbsp;</td><td><tt>1</tt></td><td><tt>--------</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>XLAT&nbsp;&nbsp;&nbsp;&nbsp;translation-table</tt><br>
<tt>XLATB&nbsp;&nbsp;&nbsp;(masm&nbsp;5.x)</tt>
</dd>
<dt>Modifies flags</dt><dd>None</dd>
</dl>
<p>
Replaces the byte in AL with byte from a user table addressed by<br>
BX.  The original value of AL is the index into the translate table.
</p></div>

<h4><a name="xor">XOR - Exclusive OR</a></h4>
<table border="1">
<tbody>
<tr><th><tt>mnemonics</tt></th><th><tt>op xx xx xx xx xx</tt></th><th><tt>sw</tt></th><th><tt>len</tt></th><th><tt>flags</tt></th></tr>
<tr><td><tt>XOR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;AL,ib</tt></td><td><tt>34 i0</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2</tt></td><td><tt>0---szap</tt></td></tr>
<tr><td><tt>XOR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;AX,iw</tt></td><td><tt>35 i0 i1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>3</tt></td><td><tt>0---szap</tt></td></tr>
<tr><td><tt>XOR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rb,rmb</tt></td><td><tt>32 mr d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2~4</tt></td><td><tt>0---szap</tt></td></tr>
<tr><td><tt>XOR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rw,rmw</tt></td><td><tt>33 mr d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>0---szap</tt></td></tr>
<tr><td><tt>XOR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb,ib</tt></td><td><tt>80 /6 d0 d1 i0</tt></td><td><tt>NB</tt></td><td><tt>3~5</tt></td><td><tt>0---szap</tt></td></tr>
<tr><td><tt>XOR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,iw</tt></td><td><tt>81 /6 d0 d1 i0 i1</tt></td><td><tt>NW</tt></td><td><tt>4~6</tt></td><td><tt>0---szap</tt></td></tr>
<tr><td><tt>XOR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,ib</tt></td><td><tt>83 /6 d0 d1 i0</tt></td><td><tt>EW</tt></td><td><tt>3~5</tt></td><td><tt>0---szap</tt></td></tr>
<tr><td><tt>XOR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmb,rb</tt></td><td><tt>30 mr d0 d1</tt></td><td><tt>&nbsp;B</tt></td><td><tt>2~4</tt></td><td><tt>0---szap</tt></td></tr>
<tr><td><tt>XOR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rmw,rw</tt></td><td><tt>31 mr d0 d1</tt></td><td><tt>&nbsp;W</tt></td><td><tt>2~4</tt></td><td><tt>0---szap</tt></td></tr>
</tbody>
</table>
<div>
<dl>
<dt>Usage</dt><dd><tt>XOR&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dest,src</tt></dd>
<dt>Modifies flags</dt><dd>CF OF PF SF ZF (AF undefined)</dd>
</dl>
<p>
Performs a bitwise exclusive OR of the operands and returns<br>
the result in the destination.
</p></div>


</body><grammarly-desktop-integration data-grammarly-shadow-root="true"></grammarly-desktop-integration></html>
