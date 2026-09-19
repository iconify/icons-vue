<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iuOS64c)" class="e1clkrbtt"/><path fill="url(#imMiODe)" class="e1clkrbtt"/><path fill="url(#iW2DIPP)" class="e1clkrbtt"/><path fill="url(#ifu3I0b)" class="hacha0yer"/><path fill="url(#isHOdYb)" class="hacha0yer"/><path fill="url(#i2k1sqc)" clip-rule="evenodd" class="fiv2pob6r"/><path fill="url(#iqkxRAb)" clip-rule="evenodd" class="fiv2pob6r"/><path fill="url(#iLJ8xcd)" clip-rule="evenodd" class="fiv2pob6r"/><path fill="url(#i7riVbe)" clip-rule="evenodd" class="h-7ur2wgi"/><path fill="url(#ivGXzTb)" clip-rule="evenodd" class="h-7ur2wgi"/><path fill="url(#i81MLfe)" clip-rule="evenodd" class="ra2djkgyn"/><path fill="url(#iOVg6se)" clip-rule="evenodd" class="xztpqlb4q"/><path fill="url(#iXzzzbb)" class="mscakbfgn"/><path fill="url(#is56Hhe)" class="mscakbfgn"/><path fill="url(#iKKCBze)" class="oe59amnru"/><path fill="url(#i01CBhc)" class="vcj1j0qxm"/><path fill="url(#iLPHT6c)" class="gy0a7w9jg"/><path fill="url(#i9vxtvc)" clip-rule="evenodd" class="b5y4sbceq"/><path fill="url(#i7x49Ne)" clip-rule="evenodd" class="sbonpib-z"/><defs><radialGradient id="isHOdYb" cx="0" cy="0" r="1" gradientTransform="matrix(1.32141 7.18624 -4.8728 .89602 11.332 17.596)" gradientUnits="userSpaceOnUse"><stop offset=".514" class="xhn5dob4p"/><stop offset="1" class="bk23iom5i"/></radialGradient><radialGradient id="i2k1sqc" cx="0" cy="0" r="1" gradientTransform="matrix(-14.99996 13.87505 -8.98464 -9.71306 20.375 13.313)" gradientUnits="userSpaceOnUse"><stop offset=".474" class="nt77fqbav"/><stop offset=".56" class="h7w4vxbvy"/><stop offset=".646" class="lfj2bx__t"/><stop offset=".739" class="qw4e_bh2z"/><stop offset=".835" class="csouh9bgg"/></radialGradient><radialGradient id="iqkxRAb" cx="0" cy="0" r="1" gradientTransform="rotate(-163.465 15.514 9.042)scale(8.3451 5.67372)" gradientUnits="userSpaceOnUse"><stop offset=".369" class="phn04tjck"/><stop offset=".909" class="lkldsdbto"/></radialGradient><radialGradient id="iLJ8xcd" cx="0" cy="0" r="1" gradientTransform="matrix(1.75 3.125 -2.12465 1.1898 14.563 7)" gradientUnits="userSpaceOnUse"><stop offset=".369" class="phn04tjck"/><stop offset="1" class="bv4qpyb7x"/></radialGradient><radialGradient id="i7riVbe" cx="0" cy="0" r="1" gradientTransform="rotate(147.858 7.462 9.46)scale(16.6818 6.7172)" gradientUnits="userSpaceOnUse"><stop offset=".281" class="p4k0zwztd"/><stop offset=".423" class="i8b4zbbkd"/></radialGradient><radialGradient id="ivGXzTb" cx="0" cy="0" r="1" gradientTransform="rotate(163.892 9.206 10.63)scale(14.0517 11.275)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="p4k0zwztd"/><stop offset=".443" class="i8b4zbbkd"/></radialGradient><radialGradient id="i81MLfe" cx="0" cy="0" r="1" gradientTransform="matrix(.03125 2.15625 -2.40439 .03485 16.281 10.031)" gradientUnits="userSpaceOnUse"><stop offset=".14" class="vc--wpv5i"/><stop offset=".845" class="stui2mbih"/></radialGradient><radialGradient id="iOVg6se" cx="0" cy="0" r="1" gradientTransform="matrix(3 -1.5 1.67262 3.34523 12.688 15.375)" gradientUnits="userSpaceOnUse"><stop offset=".14" class="vc--wpv5i"/><stop offset=".845" class="stui2mbih"/></radialGradient><radialGradient id="iXzzzbb" cx="0" cy="0" r="1" gradientTransform="rotate(109.09 4.567 10.733)scale(.6738)" gradientUnits="userSpaceOnUse"><stop class="a6l_g1b4c"/><stop offset="1" class="j761y9baf"/></radialGradient><radialGradient id="is56Hhe" cx="0" cy="0" r="1" gradientTransform="rotate(112.736 4.55 10.311)scale(.93205)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="wjs6k_jsv"/><stop offset=".832" class="r8wgxkbjb"/></radialGradient><radialGradient id="iKKCBze" cx="0" cy="0" r="1" gradientTransform="rotate(138.077 10.666 11.54)scale(12.348 7.22362)" gradientUnits="userSpaceOnUse"><stop offset=".153" class="vo20bgwli"/><stop offset=".574" class="khgeopb9j"/><stop offset=".811" class="z2fey8bsp"/><stop offset="1" class="jsu4qx-5t"/></radialGradient><radialGradient id="i01CBhc" cx="0" cy="0" r="1" gradientTransform="rotate(-160.919 5.886 3.477)scale(10.5152 20.9913)" gradientUnits="userSpaceOnUse"><stop offset=".267" class="xomd6_j3f"/><stop offset=".651" class="mm3zuyb1y"/><stop offset=".827" class="vwb5wgb7x"/></radialGradient><radialGradient id="iLPHT6c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.93602 2.37502 -5.56398 -9.22097 25.436 9.75)" gradientUnits="userSpaceOnUse"><stop offset=".595" class="mm3zuyb1y"/><stop offset=".858" class="xomd6_j3f"/></radialGradient><radialGradient id="i9vxtvc" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.35669 -4.12786 0 12.875 16.563)" gradientUnits="userSpaceOnUse"><stop offset=".018" class="i9xx-5bxe"/><stop offset=".45" class="kizrvacqz"/><stop offset=".697" class="ay3ugmp0d"/><stop offset=".875" class="ak3psp6zs"/></radialGradient><radialGradient id="i7x49Ne" cx="0" cy="0" r="1" gradientTransform="matrix(0 11.2994 -13.2218 0 17.85 19.548)" gradientUnits="userSpaceOnUse"><stop offset=".608" class="zcrjlrbaj"/><stop offset=".702" class="ffua1wu7f"/><stop offset=".87" class="ffua1wu7f"/><stop offset=".99" class="zcrjlrbaj"/></radialGradient><linearGradient id="iuOS64c" x1="18.615" x2="17.251" y1="11.095" y2="11.824" gradientUnits="userSpaceOnUse"><stop class="cjd26qb7f"/><stop offset=".404" class="nehmpodna"/><stop offset=".48" class="nehmpodna"/><stop offset=".763" class="j90z2hh9h"/><stop offset="1" class="m_zeamn-o"/></linearGradient><linearGradient id="imMiODe" x1="17.147" x2="17.645" y1="11.824" y2="11.118" gradientUnits="userSpaceOnUse"><stop offset=".333" class="m_zeamn-o"/><stop offset=".754" class="yb_1siuyt"/></linearGradient><linearGradient id="iW2DIPP" x1="17.181" x2="17.645" y1="11.824" y2="11.118" gradientUnits="userSpaceOnUse"><stop offset=".439" class="mibvldbyt"/><stop offset=".595" class="yb_1siuyt"/></linearGradient><linearGradient id="ifu3I0b" x1="8.377" x2="8.377" y1="4.111" y2="22.272" gradientUnits="userSpaceOnUse"><stop class="n8ydckv4o"/><stop offset="1" class="frkejqb1f"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:phoenix-bird" /></template>
<style>
.a6l_g1b4c {
  stop-color: var(--svg-color--8a6f99, #8A6F99);
}

.ak3psp6zs {
  stop-color: var(--svg-color--d98616, #D98616);
}

.ay3ugmp0d {
  stop-color: var(--svg-color--ee9d28, #EE9D28);
}

.b5y4sbceq {
  fill-rule: evenodd;
  d: path("M14.154 23.92c-1.778-1.075-3.22-3.164-2.8-5.622c.015-.089.132-.11.18-.034c.229.356.687 1.028.861.963c.063-.023.054-.178.037-.461c-.039-.647-.117-1.962.527-3.895c.266-.799.004-1.702-.713-2.144a1.67 1.67 0 0 0-2.141.328a7.1 7.1 0 0 0-1.059 3.723a7.55 7.55 0 0 0 5.108 7.141");
}

.bk23iom5i {
  stop-color: var(--svg-color--e53550, #E53550);
  stop-opacity: 0;
}

.bv4qpyb7x {
  stop-color: var(--svg-color--ff772a, #FF772A);
  stop-opacity: 0;
}

.cjd26qb7f {
  stop-color: var(--svg-color--ffb02e, #FFB02E);
}

.csouh9bgg {
  stop-color: var(--svg-color--f63a61, #F63A61);
}

.e1clkrbtt {
  d: path("m16.542 10.959l1.235.823c.138.092.325.026.337-.14c.09-1.185-1.117-2.69-1.73-3.15z");
}

.ffua1wu7f {
  stop-color: var(--svg-color--ffb82e, #FFB82E);
}

.fiv2pob6r {
  fill-rule: evenodd;
  d: path("M26.014 20.28a4.6 4.6 0 0 0-.72-1.792c-.807-1.2-2.441-3.567-3.089-4.033a1.78 1.78 0 0 0-1.97-.079c-2.287 1.397-4.652 1.397-4.652 1.397a1.006 1.006 0 0 1-.805-1.61l2.094-2.792a2.01 2.01 0 0 0-.425-2.833l-3.88-2.822s0 2.011 1.005 3.017l-2.89 3.513a7.14 7.14 0 0 0-1.636 4.532c0 4.17 3.385 7.55 7.556 7.543a7.5 7.5 0 0 0 3.813-1.037l.003-.002l.12-.072l1.03-.62a.78.78 0 0 1 .95.116c.31.313.303.824-.044 1.096a9.5 9.5 0 0 1-5.885 2.028a9.5 9.5 0 0 1-5.023-1.426c-.218-.135-.508.017-.508.273q0 .071.033.135c.237.44 1.773 3.029 4.995 3.029c0 0-1.086.362-2.03.472c-.178.02-.248.226-.09.31c1.353.702 4.416.584 5.137.223c0 0-.389.778-1.597 1.65c-.16.115-.088.372.11.366c4.68-.153 8.527-4.292 8.527-9.055q0-.78-.129-1.527");
}

.frkejqb1f {
  stop-color: var(--svg-color--d83152, #D83152);
}

.ft5dv1b6b {
  fill: none;
}

.gy0a7w9jg {
  d: path("M29.003 15.715c-.167.891-.537 2.379-1.293 3.636c2.485-2.002 4.043-5.113 2.918-9.625c-.064-.255-.418-.237-.475.018c-.175.777-.327 1.104-.58 1.62c-.047.095-.197.062-.2-.045c-.068-3.021-.844-5.874-2.015-7.465c-.134-.182-.4-.08-.4.146v2.599c0 .115-.187.15-.233.045c-.618-1.427-2.537-4.985-6.575-5.799c-.253-.05-.38.27-.178.43c.933.736 2.085 1.837 2.86 3.275c1.632 2.405 2.683 6.118 2.763 8.353c.005.156.176.251.305.164c.662-.452 1.043-.936 1.252-1.283c.057-.095.263-.06.27.05c.059.95.136 2.942-.149 4.211c-.04.183.151.333.3.22c.31-.236.665-.54.957-.801c.208-.184.523-.022.473.25");
}

.h-7ur2wgi {
  fill-opacity: var(--svg-fill-opacity--0-7, 0.7);
  fill-rule: evenodd;
  d: path("M26.014 20.28a4.6 4.6 0 0 0-.72-1.792c-.807-1.2-2.441-3.567-3.089-4.033a1.78 1.78 0 0 0-1.97-.079c-2.287 1.397-4.652 1.397-4.652 1.397a1.006 1.006 0 0 1-.805-1.61l2.094-2.792a2.01 2.01 0 0 0-.425-2.833l-3.88-2.822s0 2.011 1.005 3.017l-2.89 3.513a7.14 7.14 0 0 0-1.636 4.532c0 4.17 3.385 7.55 7.556 7.543a7.5 7.5 0 0 0 3.813-1.037l.003-.002l.12-.072l1.03-.62a.78.78 0 0 1 .95.116c.31.313.303.824-.044 1.096a9.5 9.5 0 0 1-5.885 2.028a9.5 9.5 0 0 1-5.023-1.426c-.218-.135-.508.017-.508.273q0 .071.033.135c.237.44 1.773 3.029 4.995 3.029c0 0-1.086.362-2.03.472c-.178.02-.248.226-.09.31c1.353.702 4.416.584 5.137.223c0 0-.389.778-1.597 1.65c-.16.115-.088.372.11.366c4.68-.153 8.527-4.292 8.527-9.055q0-.78-.129-1.527");
}

.h7w4vxbvy {
  stop-color: var(--svg-color--f2523c, #F2523C);
}

.hacha0yer {
  d: path("M1.372 9.726c.064-.255.418-.237.475.018c.175.777.327 1.104.58 1.62c.048.095.197.062.2-.045c.068-3.021.844-5.874 2.015-7.465c.134-.182.4-.08.4.146v2.599c0 .115.187.15.233.045c.618-1.427 2.537-4.985 6.575-5.799c.253-.05.38.27.178.43c-1.534 1.21-3.662 3.407-3.728 6.466c-.106 4.841 3.182 6.636 4.698 7.28q.174.074.35.137a3.67 3.67 0 0 1-1.68 7.089h-.005C6.493 21.672-.725 18.13 1.373 9.725");
}

.i8b4zbbkd {
  stop-color: var(--svg-color--ff6745, #FF6745);
  stop-opacity: 0;
}

.i9xx-5bxe {
  stop-color: var(--svg-color--ffb240, #FFB240);
}

.j761y9baf {
  stop-color: var(--svg-color--532c46, #532C46);
}

.j90z2hh9h {
  stop-color: var(--svg-color--fc7931, #FC7931);
}

.jsu4qx-5t {
  stop-color: var(--svg-color--b80013, #B80013);
}

.khgeopb9j {
  stop-color: var(--svg-color--ef4152, #EF4152);
}

.kizrvacqz {
  stop-color: var(--svg-color--ffb137, #FFB137);
}

.lfj2bx__t {
  stop-color: var(--svg-color--c42530, #C42530);
}

.lkldsdbto {
  stop-color: var(--svg-color--f63a61, #F63A61);
  stop-opacity: 0;
}

.m_zeamn-o {
  stop-color: var(--svg-color--e56447, #E56447);
}

.mibvldbyt {
  stop-color: var(--svg-color--dc568e, #DC568E);
}

.mm3zuyb1y {
  stop-color: var(--svg-color--ffad36, #FFAD36);
}

.mscakbfgn {
  d: path("M15.583 10.744a.503.503 0 1 0 0-1.006a.503.503 0 0 0 0 1.006");
}

.n8ydckv4o {
  stop-color: var(--svg-color--fd3a47, #FD3A47);
}

.nehmpodna {
  stop-color: var(--svg-color--ffc27a, #FFC27A);
}

.nt77fqbav {
  stop-color: var(--svg-color--ff7628, #FF7628);
}

.oe59amnru {
  d: path("M30.628 9.726c-.064-.255-.418-.237-.475.019c-.174.777-.327 1.103-.58 1.618c-.047.096-.197.063-.199-.044c-.07-3.021-.845-5.874-2.016-7.465c-.134-.182-.4-.08-.4.146v2.599c0 .115-.187.15-.232.045c-.619-1.427-2.538-4.985-6.576-5.798c-.253-.051-.38.268-.178.428c1.534 1.212 3.662 3.41 3.728 6.468c.106 4.841-3.182 6.636-4.698 7.28a7 7 0 0 1-.35.137a3.67 3.67 0 0 0 1.68 7.089h.005c5.17-.575 12.388-4.117 10.29-12.522");
}

.p4k0zwztd {
  stop-color: var(--svg-color--de3e0d, #DE3E0D);
}

.phn04tjck {
  stop-color: var(--svg-color--ff6723, #FF6723);
}

.qw4e_bh2z {
  stop-color: var(--svg-color--ca3842, #CA3842);
}

.r8wgxkbjb {
  stop-color: var(--svg-color--4e252d, #4E252D);
}

.ra2djkgyn {
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  fill-rule: evenodd;
  d: path("M26.014 20.28a4.6 4.6 0 0 0-.72-1.792c-.807-1.2-2.441-3.567-3.089-4.033a1.78 1.78 0 0 0-1.97-.079c-2.287 1.397-4.652 1.397-4.652 1.397a1.006 1.006 0 0 1-.805-1.61l2.094-2.792a2.01 2.01 0 0 0-.425-2.833l-3.88-2.822s0 2.011 1.005 3.017l-2.89 3.513a7.14 7.14 0 0 0-1.636 4.532c0 4.17 3.385 7.55 7.556 7.543a7.5 7.5 0 0 0 3.813-1.037l.003-.002l.12-.072l1.03-.62a.78.78 0 0 1 .95.116c.31.313.303.824-.044 1.096a9.5 9.5 0 0 1-5.885 2.028a9.5 9.5 0 0 1-5.023-1.426c-.218-.135-.508.017-.508.273q0 .071.033.135c.237.44 1.773 3.029 4.995 3.029c0 0-1.086.362-2.03.472c-.178.02-.248.226-.09.31c1.353.702 4.416.584 5.137.223c0 0-.389.778-1.597 1.65c-.16.115-.088.372.11.366c4.68-.153 8.527-4.292 8.527-9.055q0-.78-.129-1.527");
}

.sbonpib-z {
  fill-rule: evenodd;
  d: path("M24.636 26.79c-.987.77-2.551 1.697-4.237 2.12a.192.192 0 0 1-.216-.276l.611-1.223a.201.201 0 0 0-.236-.282a45 45 0 0 1-2.773.715c-.204.045-.31-.2-.144-.325l.934-.7c.089-.067.015-.23-.095-.214c-.57.09-1.532.165-2.48-.105c-.627-.179-1.104-.469-1.486-.896a9.5 9.5 0 0 1-2.948-1.2c-.218-.135-.508.017-.508.273q0 .071.032.135c.238.44 1.774 3.029 4.996 3.029c0 0-1.086.362-2.03.472c-.178.02-.248.226-.09.31c1.353.702 4.416.584 5.137.223c0 0-.389.778-1.597 1.65c-.16.115-.088.372.11.366c2.898-.095 5.477-1.718 7.02-4.071");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vcj1j0qxm {
  d: path("M2.998 15.715c.166.891.535 2.379 1.292 3.636C1.805 17.35.247 14.238 1.372 9.726c.064-.255.418-.237.475.018c.175.777.327 1.104.58 1.62c.048.095.197.062.2-.045c.068-3.021.844-5.874 2.015-7.465c.134-.182.4-.08.4.146v2.599c0 .115.187.15.233.045c.618-1.427 2.537-4.985 6.575-5.799c.253-.05.38.27.178.43c-.933.736-2.085 1.837-2.86 3.275c-1.632 2.405-2.683 6.118-2.763 8.353c-.005.156-.176.251-.305.164c-.662-.452-1.043-.936-1.252-1.283c-.057-.095-.263-.06-.27.05c-.059.95-.136 2.942.148 4.211c.041.183-.15.333-.3.22c-.309-.236-.664-.54-.956-.801c-.208-.184-.523-.022-.472.25");
}

.vo20bgwli {
  stop-color: var(--svg-color--fb4b5c, #FB4B5C);
}

.vwb5wgb7x {
  stop-color: var(--svg-color--e09624, #E09624);
}

.wjs6k_jsv {
  stop-color: var(--svg-color--695c5f, #695C5F);
}

.xhn5dob4p {
  stop-color: var(--svg-color--be1a22, #BE1A22);
}

.xomd6_j3f {
  stop-color: var(--svg-color--ffc14a, #FFC14A);
}

.xztpqlb4q {
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  fill-rule: evenodd;
  d: path("M26.014 20.28a4.6 4.6 0 0 0-.72-1.792c-.807-1.2-2.441-3.567-3.089-4.033a1.78 1.78 0 0 0-1.97-.079c-2.287 1.397-4.652 1.397-4.652 1.397a1.006 1.006 0 0 1-.805-1.61l2.094-2.792a2.01 2.01 0 0 0-.425-2.833l-3.88-2.822s0 2.011 1.005 3.017l-2.89 3.513a7.14 7.14 0 0 0-1.636 4.532c0 4.17 3.385 7.55 7.556 7.543a7.5 7.5 0 0 0 3.813-1.037l.003-.002l.12-.072l1.03-.62a.78.78 0 0 1 .95.116c.31.313.303.824-.044 1.096a9.5 9.5 0 0 1-5.885 2.028a9.5 9.5 0 0 1-5.023-1.426c-.218-.135-.508.017-.508.273q0 .071.033.135c.237.44 1.773 3.029 4.995 3.029c0 0-1.086.362-2.03.472c-.178.02-.248.226-.09.31c1.353.702 4.416.584 5.137.223c0 0-.389.778-1.597 1.65c-.16.115-.088.372.11.366c4.68-.153 8.527-4.292 8.527-9.055q0-.78-.129-1.527");
}

.yb_1siuyt {
  stop-color: var(--svg-color--e56447, #E56447);
  stop-opacity: 0;
}

.z2fey8bsp {
  stop-color: var(--svg-color--d93142, #D93142);
}

.zcrjlrbaj {
  stop-color: var(--svg-color--f6962c, #F6962C);
}

</style>
