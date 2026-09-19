<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iIkB5vc)" class="fm205i8ap"/><path fill="url(#ipuJO2c)" class="fm205i8ap"/><path fill="url(#i1HwPLe)" class="fm205i8ap"/><path fill="url(#iNsmr2c)" class="fm205i8ap"/><path fill="url(#icSgUgd)" class="j6x2chbzz"/><path fill="url(#iHBx30b)" class="j6x2chbzz"/><path fill="url(#isbZsBd)" class="j6x2chbzz"/><path fill="url(#ifDDR8w)" class="j6x2chbzz"/><path fill="url(#iqjCnHb)" class="gzeo4vbdi"/><path fill="url(#iQ0toIa)" class="gzeo4vbdi"/><path fill="url(#i6Dv1Me)" class="gzeo4vbdi"/><path fill="url(#imD3Qxb)" class="gzeo4vbdi"/><path fill="url(#i4dJEgK)" class="gzeo4vbdi"/><path fill="url(#ivuEnnb)" class="gzeo4vbdi"/><path fill="url(#ii3DHle)" class="gzeo4vbdi"/><path fill="url(#iJ3wphe)" class="gzeo4vbdi"/><path fill="url(#ivQsomd)" class="gzeo4vbdi"/><path fill="url(#ivsYrHc)" class="gzeo4vbdi"/><path fill="url(#iFTHXgc)" class="grynj8bgy"/><path fill="url(#iieNlGc)" class="grynj8bgy"/><path fill="url(#iGqZZrd)" class="xhmricn3w"/><path fill="url(#inLDZ8b)" class="xhmricn3w"/><path fill="url(#irzONgF)" class="xhmricn3w"/><path fill="url(#ihPi8TG)" class="h138yfbjk"/><path fill="url(#iQHsVpb)" class="h138yfbjk"/><path fill="url(#inEN0hC)" class="ajmcnbcuq"/><path fill="url(#iJqB83c)" class="ajmcnbcuq"/><path fill="url(#iwKqsFI)" class="ajmcnbcuq"/><path fill="url(#idBPezd)" class="znst0hbxg"/><path fill="url(#iW5ksCL)" class="znst0hbxg"/><path fill="url(#iSnTPJe)" class="znst0hbxg"/><g filter="url(#iEf5FCe)"><path fill="url(#ivr4x1E)" class="bbn2rjb8m"/></g><g filter="url(#ia8yGNb)"><path stroke="url(#i8FQqYb)" class="rwwy1dtsz"/></g><g filter="url(#i8yZKge)"><path stroke="url(#i3UV79c)" class="i51s4ulqg"/></g><g filter="url(#iDQtrue)"><circle fill="url(#iEpCLtd)" class="chz-ezbsx"/></g><g filter="url(#iXuQokb)"><path fill="url(#iSpOhVd)" class="w504bmk9q"/></g><path fill="url(#iOKNvqd)" class="b-laq3qyz"/><path fill="url(#iOKNvqd)" class="joj0zyefh"/><path fill="url(#iOKNvqd)" class="t-fy98b4s"/><g filter="url(#i8y2P2d)"><path stroke="url(#iJTvV2b)" class="fdujgkbcz"/></g><g filter="url(#i0mHxPb)"><path fill="url(#iO3gQue)" class="uyucbm5hw"/></g><defs><linearGradient id="iIkB5vc" x1="17.938" x2="19.938" y1="23.688" y2="29.906" gradientUnits="userSpaceOnUse"><stop class="i57cw5hsg"/><stop offset="1" class="rkmdtccts"/></linearGradient><linearGradient id="ipuJO2c" x1="19.375" x2="19.375" y1="30.203" y2="29.313" gradientUnits="userSpaceOnUse"><stop offset=".085" class="u_flnbb3o"/><stop offset="1" class="qyyzo7brh"/></linearGradient><linearGradient id="i1HwPLe" x1="21.125" x2="20.359" y1="27.906" y2="27.906" gradientUnits="userSpaceOnUse"><stop class="b9oz49bvu"/><stop offset="1" class="wm9p2nl9u"/></linearGradient><linearGradient id="iNsmr2c" x1="16.922" x2="17.266" y1="26.719" y2="26.719" gradientUnits="userSpaceOnUse"><stop class="khcqbdbiv"/><stop offset="1" class="i8fba9m3q"/></linearGradient><linearGradient id="icSgUgd" x1="15.594" x2="14.406" y1="23.656" y2="27.625" gradientUnits="userSpaceOnUse"><stop class="i57cw5hsg"/><stop offset="1" class="rkmdtccts"/></linearGradient><linearGradient id="iHBx30b" x1="11.688" x2="12.469" y1="27.906" y2="27.906" gradientUnits="userSpaceOnUse"><stop class="b9oz49bvu"/><stop offset="1" class="wm9p2nl9u"/></linearGradient><linearGradient id="isbZsBd" x1="16.109" x2="15.695" y1="26.719" y2="26.719" gradientUnits="userSpaceOnUse"><stop class="khcqbdbiv"/><stop offset="1" class="i8fba9m3q"/></linearGradient><linearGradient id="ifDDR8w" x1="14.375" x2="14.375" y1="30.203" y2="29.313" gradientUnits="userSpaceOnUse"><stop offset=".085" class="u_flnbb3o"/><stop offset="1" class="qyyzo7brh"/></linearGradient><linearGradient id="iqjCnHb" x1="12.313" x2="12.313" y1="22.656" y2="13.469" gradientUnits="userSpaceOnUse"><stop class="f1trsnm_p"/><stop offset="1" class="tza50kbse"/></linearGradient><linearGradient id="iQ0toIa" x1="4.75" x2="7.875" y1="16" y2="16" gradientUnits="userSpaceOnUse"><stop class="os3ucbcil"/><stop offset="1" class="e2tuh6bbk"/></linearGradient><linearGradient id="ivuEnnb" x1="18.625" x2="18.625" y1="30.656" y2="29.219" gradientUnits="userSpaceOnUse"><stop class="kee9yeatr"/><stop offset="1" class="fepgm7btg"/></linearGradient><linearGradient id="iFTHXgc" x1="21.906" x2="23.09" y1="27.5" y2="27.278" gradientUnits="userSpaceOnUse"><stop class="mbk6elbxt"/><stop offset="1" class="n2-g0-b3c"/></linearGradient><linearGradient id="iieNlGc" x1="21.438" x2="22.719" y1="23.203" y2="25.687" gradientUnits="userSpaceOnUse"><stop class="t06kxwbyt"/><stop offset="1" class="t7wdy7bsf"/></linearGradient><linearGradient id="iGqZZrd" x1="8.906" x2="6.688" y1="11.469" y2="11.469" gradientUnits="userSpaceOnUse"><stop class="uqvdsge3b"/><stop offset="1" class="a3p423bgx"/></linearGradient><linearGradient id="inLDZ8b" x1="8.75" x2="8.078" y1="7.719" y2="7.719" gradientUnits="userSpaceOnUse"><stop class="l5vbhlwzm"/><stop offset="1" class="xi797bkio"/></linearGradient><linearGradient id="inEN0hC" x1="10.938" x2="10.094" y1="27.266" y2="27.094" gradientUnits="userSpaceOnUse"><stop class="zxz-q9kqo"/><stop offset="1" class="e23znvbvk"/></linearGradient><linearGradient id="iJqB83c" x1="6.594" x2="7.125" y1="27.156" y2="27.266" gradientUnits="userSpaceOnUse"><stop class="zxz-q9kqo"/><stop offset="1" class="e23znvbvk"/></linearGradient><linearGradient id="iwKqsFI" x1="7.938" x2="7.75" y1="22.531" y2="23.75" gradientUnits="userSpaceOnUse"><stop class="ih4bwqbwz"/><stop offset="1" class="w_qspabqk"/></linearGradient><linearGradient id="iSnTPJe" x1="6.402" x2="6.058" y1="3.045" y2="2.826" gradientUnits="userSpaceOnUse"><stop class="hdqm2hb9u"/><stop offset="1" class="baf63sd8y"/></linearGradient><linearGradient id="ivr4x1E" x1="29.906" x2="24.188" y1="14.125" y2="20.906" gradientUnits="userSpaceOnUse"><stop class="f7d-i49rj"/><stop offset="1" class="f5g_1yb9j"/></linearGradient><linearGradient id="i8FQqYb" x1="24.625" x2="26.547" y1="23.469" y2="31.469" gradientUnits="userSpaceOnUse"><stop class="y2jfbrblg"/><stop offset="1" class="ueiieibix"/></linearGradient><linearGradient id="i3UV79c" x1="12.938" x2="10.906" y1="20.813" y2="28.875" gradientUnits="userSpaceOnUse"><stop class="y2jfbrblg"/><stop offset="1" class="ueiieibix"/></linearGradient><linearGradient id="iSpOhVd" x1="20.5" x2="26.878" y1="23.406" y2="21.886" gradientUnits="userSpaceOnUse"><stop class="e1trm2ygx"/><stop offset="1" class="bvo7_ojfl"/></linearGradient><linearGradient id="iOKNvqd" x1="17.434" x2="17.434" y1="23.984" y2="21.906" gradientUnits="userSpaceOnUse"><stop class="i6qw49bok"/><stop offset="1" class="xgjok_uag"/></linearGradient><linearGradient id="iJTvV2b" x1="8.749" x2="7.664" y1="14.188" y2="15.645" gradientUnits="userSpaceOnUse"><stop class="k6afxsb0q"/><stop offset="1" class="qr4u-6iqd"/></linearGradient><linearGradient id="iO3gQue" x1="6.313" x2="6.313" y1="15.156" y2="31.031" gradientUnits="userSpaceOnUse"><stop class="gq8c6u8cg"/><stop offset="1" class="qxtfw39oh"/></linearGradient><radialGradient id="i6Dv1Me" cx="0" cy="0" r="1" gradientTransform="matrix(4.375 .5 -.41841 3.6611 25.188 12.625)" gradientUnits="userSpaceOnUse"><stop class="jsho328sn"/><stop offset="1" class="yrblkeb9e"/></radialGradient><radialGradient id="imD3Qxb" cx="0" cy="0" r="1" gradientTransform="matrix(2.40625 -1.09375 1.10112 2.42247 25.094 9.25)" gradientUnits="userSpaceOnUse"><stop class="hscrsfify"/><stop offset="1" class="y3rfo5bvg"/></radialGradient><radialGradient id="i4dJEgK" cx="0" cy="0" r="1" gradientTransform="rotate(152.241 13.464 8.848)scale(2.0129 5.75114)" gradientUnits="userSpaceOnUse"><stop class="iai3xhbuj"/><stop offset="1" class="dhaddub6c"/></radialGradient><radialGradient id="ii3DHle" cx="0" cy="0" r="1" gradientTransform="matrix(1.15624 -3.34375 2.19517 .75907 5.813 24.688)" gradientUnits="userSpaceOnUse"><stop class="i6qw49bok"/><stop offset="1" class="xgjok_uag"/></radialGradient><radialGradient id="iJ3wphe" cx="0" cy="0" r="1" gradientTransform="rotate(-74.982 19.421 7.456)scale(1.32656 .39664)" gradientUnits="userSpaceOnUse"><stop class="jmduxtbbb"/><stop offset="1" class="mrd39bb0o"/></radialGradient><radialGradient id="ivQsomd" cx="0" cy="0" r="1" gradientTransform="matrix(1.15625 0 0 14.8125 4.938 15.438)" gradientUnits="userSpaceOnUse"><stop class="r5nj1uode"/><stop offset=".649" class="fzyeppbhm"/></radialGradient><radialGradient id="ivsYrHc" cx="0" cy="0" r="1" gradientTransform="rotate(-117.646 20.717 2.172)scale(2.96332 7.0161)" gradientUnits="userSpaceOnUse"><stop class="ietxc9u4a"/><stop offset="1" class="b2r7k3y6j"/></radialGradient><radialGradient id="irzONgF" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12501 1.0625 -.77262 -.81808 8.75 2.5)" gradientUnits="userSpaceOnUse"><stop class="i1otbc5ox"/><stop offset="1" class="t2dn92bsp"/></radialGradient><radialGradient id="ihPi8TG" cx="0" cy="0" r="1" gradientTransform="matrix(2.21875 -1.44766 1.30939 2.00683 3.75 6.057)" gradientUnits="userSpaceOnUse"><stop class="n5ku_zdcc"/><stop offset="1" class="kkwwuebuu"/></radialGradient><radialGradient id="iQHsVpb" cx="0" cy="0" r="1" gradientTransform="rotate(-176.306 4.38 1.994)scale(6.79143 4.58425)" gradientUnits="userSpaceOnUse"><stop offset=".93" class="hsl3dqb4o"/><stop offset="1" class="sta49ccmh"/></radialGradient><radialGradient id="idBPezd" cx="0" cy="0" r="1" gradientTransform="matrix(-.40625 .5625 -.5015 -.3622 6.65 3.276)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="c4ldw6bcc"/><stop offset="1" class="e9_rv-bpy"/></radialGradient><radialGradient id="iW5ksCL" cx="0" cy="0" r="1" gradientTransform="rotate(137.643 2.702 2.952)scale(.35946 .31624)" gradientUnits="userSpaceOnUse"><stop class="baf63sd8y"/><stop offset="1" class="hdqm2hb9u"/></radialGradient><radialGradient id="iEpCLtd" cx="0" cy="0" r="1" gradientTransform="rotate(-54.932 28.807 -8.85)scale(5.76535)" gradientUnits="userSpaceOnUse"><stop offset=".611" class="e1trm2ygx"/><stop offset=".94" class="bvo7_ojfl"/></radialGradient><filter id="iEf5FCe" width="6.771" height="14.656" x="23.438" y="7.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5735" stdDeviation=".375"/></filter><filter id="ia8yGNb" width="3.144" height="8.316" x="23.975" y="21.506" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5735" stdDeviation=".25"/></filter><filter id="i8yZKge" width="2.494" height="7.712" x="9.362" y="21.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5735" stdDeviation=".125"/></filter><filter id="iDQtrue" width="7.609" height="7.609" x="16.766" y="13.703" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5735" stdDeviation=".5"/></filter><filter id="iXuQokb" width="14.281" height="18.219" x="14.125" y="13" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5735" stdDeviation="1"/></filter><filter id="i8y2P2d" width="2.106" height="2.513" x="7.087" y="13.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5735" stdDeviation=".125"/></filter><filter id="i0mHxPb" width="3.625" height="18.844" x="4.5" y="4.188" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5735" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:sauropod" /></template>
<style>
.a3p423bgx {
  stop-color: var(--svg-color--5de0a6, #5DE0A6);
  stop-opacity: 0;
}

.ajmcnbcuq {
  d: path("m11.392 24.234l.483-1.937H7.719l-.515 2.284l-.014.075l-1.107 4.903a.31.31 0 0 0 .307.347H9.6a.51.51 0 0 0 .44-.259l.92-3.68l.384-1.57a1 1 0 0 1 .048-.163");
}

.b-laq3qyz {
  d: path("m21.718 25.078l-.018-.07z");
}

.b2r7k3y6j {
  stop-color: var(--svg-color--50bca0, #50BCA0);
  stop-opacity: 0;
}

.b9oz49bvu {
  stop-color: var(--svg-color--3b9376, #3B9376);
}

.baf63sd8y {
  stop-color: var(--svg-color--5c5051, #5C5051);
}

.bbn2rjb8m {
  d: path("m25.844 8.375l.07.041c1.602.958 4.254 3.765 3.367 7.584c-.9 3.875-3.385 5.292-4.625 5.531l-.468-3.218c.78-.157 3.875-1.5 3.937-5.063c.049-2.767-1.411-4.344-2.211-4.834z");
}

.bvo7_ojfl {
  stop-color: var(--svg-color--54e494, #54E494);
}

.c4ldw6bcc {
  stop-color: var(--svg-color--433437, #433437);
}

.chz-ezbsx {
  cx: 20.57px;
  cy: 17.508px;
  r: 2.805px;
}

.dhaddub6c {
  stop-color: var(--svg-color--6ddb9c, #6DDB9C);
  stop-opacity: 0;
}

.e1trm2ygx {
  stop-color: var(--svg-color--54e494, #54E494);
  stop-opacity: 0;
}

.e23znvbvk {
  stop-color: var(--svg-color--39ba88, #39BA88);
  stop-opacity: 0;
}

.e2tuh6bbk {
  stop-color: var(--svg-color--38be83, #38BE83);
  stop-opacity: 0;
}

.e9_rv-bpy {
  stop-color: var(--svg-color--3b2838, #3B2838);
}

.f1trsnm_p {
  stop-color: var(--svg-color--4fcba2, #4FCBA2);
}

.f5g_1yb9j {
  stop-color: var(--svg-color--65e19f, #65E19F);
  stop-opacity: 0;
}

.f7d-i49rj {
  stop-color: var(--svg-color--65e19f, #65E19F);
}

.fdujgkbcz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M8.844 14.188c-.122.228-.574.91-1.406 1.812");
}

.fepgm7btg {
  stop-color: var(--svg-color--76a3c8, #76A3C8);
  stop-opacity: 0;
}

.fm205i8ap {
  d: path("M21 22.906h-4v6.5c0 .28.22.5.5.5h3c.28 0 .5-.22.5-.5z");
}

.ft5dv1b6b {
  fill: none;
}

.fzyeppbhm {
  stop-color: var(--svg-color--90ddac, #90DDAC);
  stop-opacity: 0;
}

.gq8c6u8cg {
  stop-color: var(--svg-color--3cb583, #3CB583);
}

.grynj8bgy {
  d: path("m25.44 23.427l-.085-.18l-.53-2.282l-3.97 1.079l.516 1.985a.7.7 0 0 1 .172.364l1.266 5.057c.05.23.25.39.49.39h3.21c.2 0 .49-.2.44-.39z");
}

.gzeo4vbdi {
  d: path("M30 14.876c0-3.14-1.734-6.08-4.45-7.16a.5.5 0 0 0-.49.04s-.01 0-.01.01c-.27.2-.232.528.04.78c.992.92 2.048 2.406 2.19 4.178c.064.807-.046 1.807-.6 2.534c-.444.581-1.13.868-1.68.868c-.812 0-1.28-.558-1.75-1.048c-.66-.8-1.74-1.172-2.85-1.172H9.31c-.17 0-.357-.14-.357-.31v-9.81c0-1.04-.793-1.692-1.833-1.692H4c-1.1 0-2 .712-2 1.812s.9 2 2 2h.867c.305 0 .352.278.352.356l-.094 14.654c0 1.18.565 2.21 1.565 2.69c.39.19.6.62.5 1.05l-1.1 4.87c-.05.19.1.38.3.38H9.6c.23 0 .44-.16.49-.39l1.254-5.12c.06-.29.216-.49.506-.49h9.2c.29 0 .437.2.497.49l1.265 5.057c.05.23.25.39.49.39h3.21c.2 0 .491-.2.441-.39L25.3 22.856c-.08-.36.09-.74.42-.91c2.54-1.33 4.28-4 4.28-7.07");
}

.h138yfbjk {
  d: path("M8.621 2.759L5.16 6.057c-.05-.08-.138-.15-.292-.15H4c-1.1 0-2-.9-2-2s.9-1.813 2-1.813h3.12c.633 0 1.174.241 1.501.665");
}

.hdqm2hb9u {
  stop-color: var(--svg-color--5c5051, #5C5051);
  stop-opacity: 0;
}

.hscrsfify {
  stop-color: var(--svg-color--39c780, #39C780);
}

.hsl3dqb4o {
  stop-color: var(--svg-color--afe6c0, #AFE6C0);
  stop-opacity: 0;
}

.i1otbc5ox {
  stop-color: var(--svg-color--60e89b, #60E89B);
}

.i51s4ulqg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M11.531 22.219L9.687 29.28");
}

.i57cw5hsg {
  stop-color: var(--svg-color--2c5d6e, #2C5D6E);
}

.i6qw49bok {
  stop-color: var(--svg-color--6295ad, #6295AD);
}

.i8fba9m3q {
  stop-color: var(--svg-color--13685f, #13685F);
  stop-opacity: 0;
}

.iai3xhbuj {
  stop-color: var(--svg-color--6ddb9c, #6DDB9C);
}

.ietxc9u4a {
  stop-color: var(--svg-color--50bca0, #50BCA0);
}

.ih4bwqbwz {
  stop-color: var(--svg-color--4fcca0, #4FCCA0);
}

.j6x2chbzz {
  d: path("M16 22.906h-4v6.5c0 .28.22.5.5.5h3c.28 0 .5-.22.5-.5z");
}

.jmduxtbbb {
  stop-color: var(--svg-color--8acda6, #8ACDA6);
}

.joj0zyefh {
  d: path("m21.48 24.188l-.886-3.313H12.28l-.881 3.339c.082-.188.226-.308.45-.308h9.2c.214 0 .35.109.43.282");
}

.jsho328sn {
  stop-color: var(--svg-color--39c584, #39C584);
}

.k6afxsb0q {
  stop-color: var(--svg-color--67e79f, #67E79F);
}

.kee9yeatr {
  stop-color: var(--svg-color--76a3c8, #76A3C8);
}

.khcqbdbiv {
  stop-color: var(--svg-color--13685f, #13685F);
}

.kkwwuebuu {
  stop-color: var(--svg-color--5da9a6, #5DA9A6);
  stop-opacity: 0;
}

.l5vbhlwzm {
  stop-color: var(--svg-color--58dc96, #58DC96);
}

.mbk6elbxt {
  stop-color: var(--svg-color--46b69c, #46B69C);
}

.mrd39bb0o {
  stop-color: var(--svg-color--8acda6, #8ACDA6);
  stop-opacity: 0;
}

.n2-g0-b3c {
  stop-color: var(--svg-color--46b69c, #46B69C);
  stop-opacity: 0;
}

.n5ku_zdcc {
  stop-color: var(--svg-color--5da9a6, #5DA9A6);
}

.os3ucbcil {
  stop-color: var(--svg-color--38be83, #38BE83);
}

.qr4u-6iqd {
  stop-color: var(--svg-color--67e79f, #67E79F);
  stop-opacity: 0;
}

.qxtfw39oh {
  stop-color: var(--svg-color--3cb583, #3CB583);
  stop-opacity: 0;
}

.qyyzo7brh {
  stop-color: var(--svg-color--5f6faa, #5F6FAA);
  stop-opacity: 0;
}

.r5nj1uode {
  stop-color: var(--svg-color--90ddac, #90DDAC);
}

.rkmdtccts {
  stop-color: var(--svg-color--43808b, #43808B);
}

.rwwy1dtsz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m24.625 22.156l1.844 7.016");
}

.sta49ccmh {
  stop-color: var(--svg-color--afe6c0, #AFE6C0);
}

.t-fy98b4s {
  d: path("m11.24 24.821l-.068.257h.005z");
}

.t06kxwbyt {
  stop-color: var(--svg-color--4fcc9f, #4FCC9F);
}

.t2dn92bsp {
  stop-color: var(--svg-color--60e89b, #60E89B);
  stop-opacity: 0;
}

.t7wdy7bsf {
  stop-color: var(--svg-color--50d09d, #50D09D);
  stop-opacity: 0;
}

.tza50kbse {
  stop-color: var(--svg-color--4ad482, #4AD482);
}

.u_flnbb3o {
  stop-color: var(--svg-color--5f6faa, #5F6FAA);
}

.ueiieibix {
  stop-color: var(--svg-color--67e5a7, #67E5A7);
  stop-opacity: 0;
}

.uqvdsge3b {
  stop-color: var(--svg-color--5de0a6, #5DE0A6);
}

.uyucbm5hw {
  d: path("M6 5.688h.625v15.844H6z");
}

.w_qspabqk {
  stop-color: var(--svg-color--4fcca0, #4FCCA0);
  stop-opacity: 0;
}

.w504bmk9q {
  d: path("M21.688 15h-4.563a1 1 0 0 0-1 1v1.344a1 1 0 0 0 1 1h.957a4 4 0 0 1 3.875 3.009l2.012 7.866h2.437l-3.218-12.813z");
}

.wm9p2nl9u {
  stop-color: var(--svg-color--3b9376, #3B9376);
  stop-opacity: 0;
}

.xgjok_uag {
  stop-color: var(--svg-color--51b4af, #51B4AF);
  stop-opacity: 0;
}

.xhmricn3w {
  d: path("M9.132 13.859c-.1-.056-.179-.153-.179-.263v-9.81c0-1.04-.793-1.692-1.833-1.692H4c-1.1 0-2 .712-2 1.812s.9 2 2 2h.867c.305 0 .352.278.352.356l-.08 12.541z");
}

.xi797bkio {
  stop-color: var(--svg-color--58dc96, #58DC96);
  stop-opacity: 0;
}

.y2jfbrblg {
  stop-color: var(--svg-color--67e5a7, #67E5A7);
}

.y3rfo5bvg {
  stop-color: var(--svg-color--39c780, #39C780);
  stop-opacity: 0;
}

.yrblkeb9e {
  stop-color: var(--svg-color--39c584, #39C584);
  stop-opacity: 0;
}

.znst0hbxg {
  d: path("M6.5 3.938a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

.zxz-q9kqo {
  stop-color: var(--svg-color--39ba88, #39BA88);
}

</style>
