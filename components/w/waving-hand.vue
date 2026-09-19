<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iIkMovc)" class="uq_uirbfi"/><path fill="url(#ifKU2vb)" class="vgsq4obfm"/><path fill="url(#iytAKwe)" class="sogarrbkb"/><path fill="url(#iBQe6ab)" class="sogarrbkb"/><path fill="url(#iKUmxUd)" class="sogarrbkb"/><path fill="url(#iBOT1le)" class="hgkyesbls"/><path fill="url(#iq1C4Hb)" class="hgkyesbls"/><path fill="url(#iyUg0rd)" class="hgkyesbls"/><path fill="url(#iBelJPc)" class="hgkyesbls"/><path fill="url(#iBN5UOJ)" class="hgkyesbls"/><path fill="url(#i1Ky0Fc)" class="gpm2_tb9w"/><path fill="url(#i2MNhYS)" class="gpm2_tb9w"/><path fill="url(#iBrm9gc)" class="gpm2_tb9w"/><path fill="url(#iWCJjAd)" class="gpm2_tb9w"/><path fill="url(#irM6xMe)" class="gpm2_tb9w"/><path fill="url(#irmvGSd)" class="gpm2_tb9w"/><path fill="url(#iERa3jb)" class="ejd791_gz"/><path fill="url(#iGNHeud)" class="ejd791_gz"/><path fill="url(#iAG4UWd)" class="ejd791_gz"/><path fill="url(#iu5WfQe)" class="ejd791_gz"/><path fill="url(#iiW3VzF)" class="ejd791_gz"/><path fill="url(#iE9zt0b)" class="ejd791_gz"/><path fill="url(#i5IJEch)" class="m3kzakbtz"/><path fill="url(#iu6ZSUO)" class="m3kzakbtz"/><path fill="url(#iDJplQd)" class="m3kzakbtz"/><path fill="url(#iaLd9Hd)" class="m3kzakbtz"/><path fill="url(#iOdQ1jd)" class="m3kzakbtz"/><path fill="url(#igDrjLd)" class="vgsq4obfm"/><path fill="url(#ioIrM4c)" class="vgsq4obfm"/><path fill="url(#iRFg9Oe)" class="vgsq4obfm"/><path fill="url(#ietQGvQ)" class="l1hmicbpz"/><path fill="url(#iQtzqXd)" clip-rule="evenodd" class="klijijibf"/><path fill="url(#iUeDjue)" clip-rule="evenodd" class="klijijibf"/><path fill="url(#iVebUdl)" clip-rule="evenodd" class="klijijibf"/><path fill="url(#if2qLxe)" clip-rule="evenodd" class="l54hwjhie"/><path fill="url(#igfrKkx)" clip-rule="evenodd" class="l54hwjhie"/><path fill="url(#iOZtT4c)" clip-rule="evenodd" class="mzs5aebyf"/><path fill="url(#iBMfW6w)" clip-rule="evenodd" class="mzs5aebyf"/><path fill="url(#iYvrvre)" clip-rule="evenodd" class="x6i4dtbxl"/><path fill="url(#ixvnoMi)" clip-rule="evenodd" class="x6i4dtbxl"/><g filter="url(#ipMtceK)"><path class="aaar332_c"/></g><defs><radialGradient id="iIkMovc" cx="0" cy="0" r="1" gradientTransform="matrix(10.49397 18.25002 -11.9225 6.85558 19.267 13.835)" gradientUnits="userSpaceOnUse"><stop offset=".003" class="g76irccuo"/><stop offset=".698" class="ap52qe_uy"/><stop offset=".797" class="tqj5g2b6n"/><stop offset=".945" class="fahzpvuik"/></radialGradient><radialGradient id="ifKU2vb" cx="0" cy="0" r="1" gradientTransform="matrix(-.6563 -12.47285 4.7783 -.25142 29.761 18.46)" gradientUnits="userSpaceOnUse"><stop offset=".003" class="znaucd7lm"/><stop offset="1" class="lb5l0hb7w"/></radialGradient><radialGradient id="iytAKwe" cx="0" cy="0" r="1" gradientTransform="rotate(99.682 10.113 16.685)scale(6.68903 2.56255)" gradientUnits="userSpaceOnUse"><stop offset=".003" class="znaucd7lm"/><stop offset="1" class="lb5l0hb7w"/></radialGradient><radialGradient id="iBQe6ab" cx="0" cy="0" r="1" gradientTransform="matrix(2.70547 0 0 10.9717 24.18 13.55)" gradientUnits="userSpaceOnUse"><stop class="oej2bqkth"/><stop offset="1" class="b7qix9b9k"/></radialGradient><radialGradient id="iKUmxUd" cx="0" cy="0" r="1" gradientTransform="matrix(-.32444 -4.54214 3.15487 -.22535 25.368 17.804)" gradientUnits="userSpaceOnUse"><stop class="zdvc83biv"/><stop offset="1" class="ciqclsb9g"/></radialGradient><radialGradient id="iBOT1le" cx="0" cy="0" r="1" gradientTransform="matrix(-4.1875 2.31887 -4.65816 -8.41186 22.824 10.891)" gradientUnits="userSpaceOnUse"><stop offset=".563" class="uqa__bxve"/><stop offset="1" class="yjladh7dz"/></radialGradient><radialGradient id="iyUg0rd" cx="0" cy="0" r="1" gradientTransform="matrix(3.125 -.75 1.65852 6.91053 21.824 7.085)" gradientUnits="userSpaceOnUse"><stop class="hhapa6wnv"/><stop offset="1" class="qtyb0ubhy"/></radialGradient><radialGradient id="iBelJPc" cx="0" cy="0" r="1" gradientTransform="matrix(2.62211 1.72282 -1.33572 2.03294 16.577 5.987)" gradientUnits="userSpaceOnUse"><stop class="da3huf92z"/><stop offset="1" class="y12zfjrqd"/></radialGradient><radialGradient id="i1Ky0Fc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.96122 2.36624 -4.93787 -8.2663 18.313 12.37)" gradientUnits="userSpaceOnUse"><stop offset=".563" class="uqa__bxve"/><stop offset="1" class="yjladh7dz"/></radialGradient><radialGradient id="iBrm9gc" cx="0" cy="0" r="1" gradientTransform="matrix(2.54183 -1.70758 5.19874 7.7386 17.781 9.429)" gradientUnits="userSpaceOnUse"><stop class="hhapa6wnv"/><stop offset="1" class="qtyb0ubhy"/></radialGradient><radialGradient id="iWCJjAd" cx="0" cy="0" r="1" gradientTransform="matrix(3.5 -1.625 7.41995 15.9814 15.449 13.21)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="uqa__bxve"/><stop offset="1" class="yjladh7dz"/></radialGradient><radialGradient id="irM6xMe" cx="0" cy="0" r="1" gradientTransform="matrix(2.6875 1.71877 -1.36988 2.14198 11.949 7.366)" gradientUnits="userSpaceOnUse"><stop class="da3huf92z"/><stop offset="1" class="y12zfjrqd"/></radialGradient><radialGradient id="iERa3jb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.81157 2.58981 -5.07136 -5.5056 15.635 16.37)" gradientUnits="userSpaceOnUse"><stop offset=".563" class="uqa__bxve"/><stop offset="1" class="yjladh7dz"/></radialGradient><radialGradient id="iAG4UWd" cx="0" cy="0" r="1" gradientTransform="matrix(2.84456 -.62 1.31334 6.02556 14.698 13.09)" gradientUnits="userSpaceOnUse"><stop class="hhapa6wnv"/><stop offset="1" class="qtyb0ubhy"/></radialGradient><radialGradient id="iu5WfQe" cx="0" cy="0" r="1" gradientTransform="matrix(3.09229 -2.61476 13.36754 15.80883 12.92 17.075)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="uqa__bxve"/><stop offset="1" class="yjladh7dz"/></radialGradient><radialGradient id="iiW3VzF" cx="0" cy="0" r="1" gradientTransform="matrix(2.54888 1.44229 -1.0855 1.91836 9.6 12.171)" gradientUnits="userSpaceOnUse"><stop class="da3huf92z"/><stop offset="1" class="y12zfjrqd"/></radialGradient><radialGradient id="iE9zt0b" cx="0" cy="0" r="1" gradientTransform="matrix(1.15625 -1.1875 5.3617 5.2206 11.136 17.929)" gradientUnits="userSpaceOnUse"><stop class="b1iv07bac"/><stop offset=".825" class="sh3y2ubpl"/></radialGradient><radialGradient id="i5IJEch" cx="0" cy="0" r="1" gradientTransform="matrix(-3.0158 2.24226 -4.21894 -5.67438 14.785 20.718)" gradientUnits="userSpaceOnUse"><stop offset=".563" class="uqa__bxve"/><stop offset="1" class="yjladh7dz"/></radialGradient><radialGradient id="iu6ZSUO" cx="0" cy="0" r="1" gradientTransform="matrix(3.0512 -.53678 .93252 5.30068 13.779 17.877)" gradientUnits="userSpaceOnUse"><stop class="hhapa6wnv"/><stop offset="1" class="qtyb0ubhy"/></radialGradient><radialGradient id="iDJplQd" cx="0" cy="0" r="1" gradientTransform="rotate(-34.314 40.477 -8.562)scale(4.01583 19.3881)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="uqa__bxve"/><stop offset="1" class="yjladh7dz"/></radialGradient><radialGradient id="iaLd9Hd" cx="0" cy="0" r="1" gradientTransform="matrix(2.73403 1.24873 -.82863 1.81424 8.31 17.083)" gradientUnits="userSpaceOnUse"><stop class="da3huf92z"/><stop offset="1" class="y12zfjrqd"/></radialGradient><radialGradient id="igDrjLd" cx="0" cy="0" r="1" gradientTransform="matrix(-10.93755 13.5 -21.8324 -17.68836 23.949 12.523)" gradientUnits="userSpaceOnUse"><stop offset=".872" class="iay-_ym8b"/><stop offset="1" class="qljgqobpl"/></radialGradient><radialGradient id="ioIrM4c" cx="0" cy="0" r="1" gradientTransform="matrix(4.375 17.93747 -19.68135 4.80034 20.324 12.71)" gradientUnits="userSpaceOnUse"><stop offset=".853" class="iay-_ym8b"/><stop offset="1" class="qljgqobpl"/></radialGradient><radialGradient id="iRFg9Oe" cx="0" cy="0" r="1" gradientTransform="matrix(1.375 2.875 -2.56302 1.2258 24.511 8.023)" gradientUnits="userSpaceOnUse"><stop class="da3huf92z"/><stop offset="1" class="y12zfjrqd"/></radialGradient><radialGradient id="ietQGvQ" cx="0" cy="0" r="1" gradientTransform="rotate(149.254 10.292 10.421)scale(1.2136 3.75534)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="l68t7eblh"/><stop offset="1" class="ngd6m8c9r"/></radialGradient><radialGradient id="iQtzqXd" cx="0" cy="0" r="1" gradientTransform="matrix(2.4881 4.69345 -6.9606 3.68996 4.893 17.19)" gradientUnits="userSpaceOnUse"><stop class="qi_4zubnj"/><stop offset="1" class="fd2otuxon"/></radialGradient><radialGradient id="iUeDjue" cx="0" cy="0" r="1" gradientTransform="matrix(.75 .03125 -.06577 1.57838 3.39 17.585)" gradientUnits="userSpaceOnUse"><stop class="n_6hwcc4z"/><stop offset="1" class="wa6zhwbbl"/></radialGradient><radialGradient id="iVebUdl" cx="0" cy="0" r="1" gradientTransform="matrix(-.28125 .70313 -2.06816 -.82725 9.016 21.866)" gradientUnits="userSpaceOnUse"><stop class="n_6hwcc4z"/><stop offset="1" class="wa6zhwbbl"/></radialGradient><radialGradient id="if2qLxe" cx="0" cy="0" r="1" gradientTransform="rotate(94.712 -6.55 12.412)scale(4.2017 7.06475)" gradientUnits="userSpaceOnUse"><stop class="qi_4zubnj"/><stop offset="1" class="fd2otuxon"/></radialGradient><radialGradient id="igfrKkx" cx="0" cy="0" r="1" gradientTransform="matrix(.71542 .0298 -.06267 1.50488 1.722 19.476)" gradientUnits="userSpaceOnUse"><stop class="n_6hwcc4z"/><stop offset="1" class="wa6zhwbbl"/></radialGradient><radialGradient id="iOZtT4c" cx="0" cy="0" r="1" gradientTransform="matrix(2.21836 3.87285 -5.7436 3.28993 18.508 2.346)" gradientUnits="userSpaceOnUse"><stop class="qi_4zubnj"/><stop offset="1" class="fd2otuxon"/></radialGradient><radialGradient id="iBMfW6w" cx="0" cy="0" r="1" gradientTransform="rotate(18.861 -3.593 52.16)scale(.64211 1.03351)" gradientUnits="userSpaceOnUse"><stop class="ocxtugb2f"/><stop offset="1" class="qidinqb2y"/></radialGradient><radialGradient id="iYvrvre" cx="0" cy="0" r="1" gradientTransform="matrix(2.71428 4.83482 -7.17211 4.02645 20.387 .762)" gradientUnits="userSpaceOnUse"><stop class="qi_4zubnj"/><stop offset="1" class="fd2otuxon"/></radialGradient><radialGradient id="ixvnoMi" cx="0" cy="0" r="1" gradientTransform="rotate(18.853 2.38 57.27)scale(.61247 .98543)" gradientUnits="userSpaceOnUse"><stop class="ocxtugb2f"/><stop offset="1" class="qidinqb2y"/></radialGradient><linearGradient id="iq1C4Hb" x1="20.379" x2="20.379" y1="15.795" y2="13.21" gradientUnits="userSpaceOnUse"><stop class="uin7i86hm"/><stop offset="1" class="vj70_lxns"/></linearGradient><linearGradient id="iBN5UOJ" x1="17.074" x2="18.636" y1="12.304" y2="11.554" gradientUnits="userSpaceOnUse"><stop class="b1iv07bac"/><stop offset=".825" class="sh3y2ubpl"/></linearGradient><linearGradient id="i2MNhYS" x1="16" x2="16" y1="17.375" y2="14.737" gradientUnits="userSpaceOnUse"><stop class="uin7i86hm"/><stop offset="1" class="vj70_lxns"/></linearGradient><linearGradient id="irmvGSd" x1="13.355" x2="14.395" y1="13.835" y2="13.108" gradientUnits="userSpaceOnUse"><stop class="b1iv07bac"/><stop offset=".825" class="sh3y2ubpl"/></linearGradient><linearGradient id="iGNHeud" x1="13.442" x2="13.442" y1="20.569" y2="18.356" gradientUnits="userSpaceOnUse"><stop class="uin7i86hm"/><stop offset="1" class="vj70_lxns"/></linearGradient><linearGradient id="iOdQ1jd" x1="14.949" x2="12.432" y1="27.585" y2="22.437" gradientUnits="userSpaceOnUse"><stop class="uin7i86hm"/><stop offset="1" class="vj70_lxns"/></linearGradient><filter id="ipMtceK" width="13.608" height="15.065" x="11.923" y="11.429" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1063" stdDeviation="1"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:waving-hand" /></template>
<style>
.aaar332_c {
  stroke: var(--svg-color--ffc339, #FFC339);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M22.531 14.429c-1.937.781-6.32 3.347-7.608 9.064");
}

.ap52qe_uy {
  stop-color: var(--svg-color--ffc53f, #FFC53F);
}

.b1iv07bac {
  stop-color: var(--svg-color--a85300, #A85300);
}

.b7qix9b9k {
  stop-color: var(--svg-color--ee9f2c, #EE9F2C);
  stop-opacity: 0;
}

.ciqclsb9g {
  stop-color: var(--svg-color--ffc33a, #FFC33A);
  stop-opacity: 0;
}

.da3huf92z {
  stop-color: var(--svg-color--d99f2b, #D99F2B);
}

.ejd791_gz {
  d: path("M10.988 12.445c1.383-.688 2.4.086 2.72.508c.999 1.507 2.19 3.22 2.74 4.132c1.47 2.43-1.538 3.484-1.538 3.484c-2.766-3.117-3.278-3.274-3.477-3.427c-.106-.081-.748-1.123-1.055-1.633c-.825-1.657 0-2.761.61-3.064");
}

.fahzpvuik {
  stop-color: var(--svg-color--ec7d58, #EC7D58);
}

.fd2otuxon {
  stop-color: var(--svg-color--4b6dcb, #4B6DCB);
}

.ft5dv1b6b {
  fill: none;
}

.g76irccuo {
  stop-color: var(--svg-color--ffc133, #FFC133);
}

.gpm2_tb9w {
  d: path("M16.271 8.389c.196.432 1.548 3.392 1.423 3.142c.363.82 1.49 2.82 1.817 3.367c.724 1.206-.093 2.209-.62 2.515c-1.517.88-2.388-.242-2.388-.242c-.8-1.172-1.468-2.148-2.789-4.226c-.318-.6-.898-1.938-1.132-2.587c-.577-1.602.378-2.498.954-2.782c1.25-.579 2.438.156 2.735.813");
}

.hgkyesbls {
  d: path("M20.35 7.077c1.217 2.683 2.71 5.975 3.83 7.283c-.175 1.496-1.512 2.212-2.664 1.944c-1.453-.422-2.005-1.453-2.005-1.453s-.38-.588-.75-1.235c-.428-.748-.35-.731-1.067-2.085c-.141-.266-.831-2.07-1.04-2.799c-.328-1.36.461-2.292.962-2.532c.695-.333 2.146-.42 2.72.844z");
}

.hhapa6wnv {
  stop-color: var(--svg-color--ffec4c, #FFEC4C);
}

.iay-_ym8b {
  stop-color: var(--svg-color--f6814f, #F6814F);
  stop-opacity: 0;
}

.klijijibf {
  fill-rule: evenodd;
  d: path("M4.126 16.9a.54.54 0 0 1 .539.54c0 .9.364 2.105 1.149 3.078c.77.957 1.94 1.681 3.58 1.681a.539.539 0 0 1 0 1.078c-2.002 0-3.467-.9-4.42-2.082c-.938-1.164-1.387-2.609-1.387-3.756a.54.54 0 0 1 .539-.539");
}

.l1hmicbpz {
  d: path("M22.046 10.668c.751 1.534 1.501 2.909 2.135 3.662c.065.67.123 1.052.283 1.63c-1.265-1.266-2.49-4.033-2.418-5.292");
}

.l54hwjhie {
  fill-rule: evenodd;
  d: path("M2.448 18.823a.54.54 0 0 1 .54.54c0 1.91 1.43 4.462 4.436 4.462a.539.539 0 0 1 0 1.078c-3.78 0-5.515-3.23-5.515-5.54a.54.54 0 0 1 .54-.54");
}

.l68t7eblh {
  stop-color: var(--svg-color--b4813d, #B4813D);
}

.lb5l0hb7w {
  stop-color: var(--svg-color--ffe647, #FFE647);
  stop-opacity: 0;
}

.m3kzakbtz {
  d: path("M9.338 20.573c-1.663-2.263.743-3.822 2.095-3.43c.64.395 1.63 1.386 2.051 1.833c2.682 2.615 2.235 3.422 1.485 4.31c-.727.602-1.672 1.085-3.067 0c-.563-.438-1.953-1.882-2.564-2.713");
}

.mzs5aebyf {
  fill-rule: evenodd;
  d: path("M22.636 9.852a.54.54 0 0 1-.542-.536c-.006-.9-.378-2.103-1.169-3.071c-.777-.952-1.95-1.668-3.591-1.658a.54.54 0 0 1-.007-1.078c2.002-.013 3.473.879 4.433 2.054c.946 1.158 1.404 2.6 1.412 3.746a.54.54 0 0 1-.536.543");
}

.n_6hwcc4z {
  stop-color: var(--svg-color--5486c7, #5486C7);
}

.ngd6m8c9r {
  stop-color: var(--svg-color--b4813d, #B4813D);
  stop-opacity: 0;
}

.ocxtugb2f {
  stop-color: var(--svg-color--4d8ac1, #4D8AC1);
}

.oej2bqkth {
  stop-color: var(--svg-color--ee9f2c, #EE9F2C);
}

.qi_4zubnj {
  stop-color: var(--svg-color--419ffd, #419FFD);
}

.qidinqb2y {
  stop-color: var(--svg-color--4d8ac1, #4D8AC1);
  stop-opacity: 0;
}

.qljgqobpl {
  stop-color: var(--svg-color--f7814f, #F7814F);
}

.qtyb0ubhy {
  stop-color: var(--svg-color--ffec4c, #FFEC4C);
  stop-opacity: 0;
}

.sh3y2ubpl {
  stop-color: var(--svg-color--a85300, #A85300);
  stop-opacity: 0;
}

.sogarrbkb {
  d: path("M28.933 11.343c-.078.875-.082.845-.242 2.962c-.083 1.094.511 5.121.511 5.121c-1.445.472-4.576-.153-5.021-5.066c.219-.508.195-1.36.445-3.44c.226-1.876 1.774-2.055 2.439-1.922c1.47.307 1.917 1.796 1.868 2.345");
}

.tqj5g2b6n {
  stop-color: var(--svg-color--ffad3e, #FFAD3E);
}

.uin7i86hm {
  stop-color: var(--svg-color--ffc337, #FFC337);
}

.uq_uirbfi {
  d: path("M20.35 7.077c1.217 2.683 2.71 5.975 3.83 7.283c.22-.508.196-1.36.446-3.44c.226-1.876 1.774-2.055 2.439-1.922c1.47.307 1.917 1.796 1.868 2.345c-.078.875-.082.845-.242 2.962c-.235 3.095.96 5.432 1.07 8.082c0 4.994-4.377 7.448-7.44 7.448c-2.451 0-4.904-1.568-5.823-2.352l-4.596-4.198c-.562-.437-1.953-1.881-2.563-2.712c-1.664-2.263.742-3.822 2.094-3.43c-.106-.082-.748-1.124-1.055-1.634c-.825-1.657 0-2.76.61-3.064c1.383-.688 2.4.086 2.72.508c-.123-.208-.507-1.05-1.126-2.595c-.619-1.544.378-2.498.954-2.782c1.25-.579 2.438.156 2.735.813c.146.321.93 2.04 1.272 2.797c-.258-.628-.724-1.877-.889-2.454c-.328-1.36.461-2.292.962-2.532c.695-.333 2.146-.42 2.72.844z");
}

.uqa__bxve {
  stop-color: var(--svg-color--f09d2e, #F09D2E);
  stop-opacity: 0;
}

.vgsq4obfm {
  d: path("M20.35 7.077c1.217 2.683 2.71 5.975 3.83 7.283c.22-.508.196-1.36.446-3.44c.226-1.876 1.774-2.055 2.439-1.922c1.47.307 1.917 1.796 1.868 2.345c-.078.875-.082.845-.242 2.962c-.235 3.095.96 5.432 1.07 8.082c0 4.994-4.377 7.448-7.44 7.448c-2.451 0-4.904-1.568-5.823-2.352l-4.596-4.198c-.563-.437-1.953-1.881-2.564-2.712c-1.663-2.263.743-3.822 2.095-3.43c-.106-.082-.748-1.124-1.055-1.634c-.825-1.657 0-2.76.61-3.064c1.383-.688 2.4.086 2.72.508c-.123-.208-.507-1.05-1.126-2.595c-.619-1.544.378-2.498.954-2.782c1.25-.579 2.438.156 2.735.813c.146.321.93 2.04 1.272 2.797c-.258-.628-.724-1.877-.889-2.454c-.328-1.36.461-2.292.961-2.532c.696-.333 2.147-.42 2.72.844z");
}

.vj70_lxns {
  stop-color: var(--svg-color--ffc337, #FFC337);
  stop-opacity: 0;
}

.wa6zhwbbl {
  stop-color: var(--svg-color--5486c7, #5486C7);
  stop-opacity: 0;
}

.x6i4dtbxl {
  fill-rule: evenodd;
  d: path("M24.3 7.919a.54.54 0 0 1-.542-.536c-.013-1.91-1.46-4.454-4.466-4.434a.539.539 0 0 1-.007-1.078c3.78-.025 5.535 3.195 5.55 5.505a.54.54 0 0 1-.535.543");
}

.y12zfjrqd {
  stop-color: var(--svg-color--d99f2b, #D99F2B);
  stop-opacity: 0;
}

.yjladh7dz {
  stop-color: var(--svg-color--f09d2e, #F09D2E);
}

.zdvc83biv {
  stop-color: var(--svg-color--ffc93d, #FFC93D);
}

.znaucd7lm {
  stop-color: var(--svg-color--ffe849, #FFE849);
}

</style>
