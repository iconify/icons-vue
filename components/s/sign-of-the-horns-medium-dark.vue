<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iFYX6Kc)"><path class="xp1mkrtwj"/><path fill="url(#i35exSb)" class="dh-5lqd5o"/><path fill="url(#ibXc7Ed)" class="dh-5lqd5o"/><path fill="url(#iKHqVwr)" class="dh-5lqd5o"/><path fill="url(#ivR568d)" class="dh-5lqd5o"/></g><g filter="url(#iWqN5Ud)" class="wk1gub3hc"><path class="vg9i9_2xu"/></g><g filter="url(#iVroUTy)"><path class="moh1otbcy"/></g><rect fill="url(#iZcuq4c)" class="pwlhh4byl"/><rect fill="url(#iMc0KFd)" class="pwlhh4byl"/><rect fill="url(#iVwUr0b)" class="pvnortbhk"/><g filter="url(#iQ7g6Zc)"><rect fill="url(#iiNpjkb)" class="gtukhc44n"/><rect fill="url(#iNUg5Ec)" class="gtukhc44n"/></g><rect fill="url(#ibptEEb)" class="gtukhc44n"/><rect fill="url(#iMA8nRc)" class="gtukhc44n"/><rect fill="url(#ivZDyqd)" class="gtukhc44n"/><g filter="url(#iPTIPYd)"><rect fill="url(#iSG5USb)" class="n1h42xbld"/></g><rect fill="url(#iNvWRxb)" class="n1h42xbld"/><g filter="url(#i5CMF5b)"><path class="rspk5kbip"/></g><path fill="url(#i6FJcNe)" class="q_7t6qbvi"/><path fill="url(#idgqptd)" class="q_7t6qbvi"/><path fill="url(#i6FJcNe)" class="ohdcwacvr"/><path fill="url(#idgqptd)" class="ohdcwacvr"/><path fill="url(#if7berv)" class="q_7t6qbvi"/><path fill="url(#if7berv)" class="ohdcwacvr"/><g filter="url(#iFCSYqV)"><path stroke="url(#i877QOb)" class="qas3z0pzv"/></g><path fill="url(#iW8Rkye)" class="ntmgj10ki"/><path fill="url(#ikBhqgd)" class="ntmgj10ki"/><path fill="url(#inO9Nvd)" class="ntmgj10ki"/><path fill="url(#iX7mUwc)" class="ntmgj10ki"/><g filter="url(#i5ySEmd)"><path stroke="url(#izfrOJc)" class="t6m8ihbxo"/></g><g filter="url(#iYkSELd)"><rect class="miadccb6q"/></g><g filter="url(#iCQxxJd)"><rect class="cxyhdjb7d"/></g><defs><radialGradient id="i35exSb" cx="0" cy="0" r="1" gradientTransform="matrix(1.40994 -4.40607 5.09243 1.62958 21.363 16.563)" gradientUnits="userSpaceOnUse"><stop class="hjc9debbp"/><stop offset="1" class="g72v-pb2v"/></radialGradient><radialGradient id="ibXc7Ed" cx="0" cy="0" r="1" gradientTransform="matrix(-5.26865 0 0 -4.94397 21.909 20.944)" gradientUnits="userSpaceOnUse"><stop class="gdb0rzbwv"/><stop offset="1" class="xey_m__0s"/></radialGradient><radialGradient id="iKHqVwr" cx="0" cy="0" r="1" gradientTransform="matrix(-7.59133 6.41699 -6.71794 -7.94735 11.768 16)" gradientUnits="userSpaceOnUse"><stop class="irxw1xqtj"/><stop offset="1" class="i7m21ubvj"/></radialGradient><radialGradient id="ivR568d" cx="0" cy="0" r="1" gradientTransform="matrix(3.8524 -8.636 17.74316 7.91498 13.07 29.976)" gradientUnits="userSpaceOnUse"><stop class="uecs0-bwr"/><stop offset="1" class="efzdvbdmj"/></radialGradient><radialGradient id="iZcuq4c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.39062 3.59376 -2.77814 -2.6211 12.934 12.664)" gradientUnits="userSpaceOnUse"><stop class="r02rrubfh"/><stop offset="1" class="s-ksbeban"/></radialGradient><radialGradient id="iMc0KFd" cx="0" cy="0" r="1" gradientTransform="matrix(2.07716 0 0 1.61948 10.182 7.683)" gradientUnits="userSpaceOnUse"><stop class="rpzexvboz"/><stop offset="1" class="yogzn9brn"/></radialGradient><radialGradient id="iVwUr0b" cx="0" cy="0" r="1" gradientTransform="matrix(2.5 0 0 2.21875 24.298 4.063)" gradientUnits="userSpaceOnUse"><stop class="xjwesibys"/><stop offset="1" class="xa6cjn3la"/></radialGradient><radialGradient id="iNUg5Ec" cx="0" cy="0" r="1" gradientTransform="matrix(-1.31357 .85703 -1.14666 -1.7575 16.472 9.946)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="kx20wlbbb"/><stop offset="1" class="lfcqr7rkc"/></radialGradient><radialGradient id="ibptEEb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.11578 6.51664 0 13.426 17.207)" gradientUnits="userSpaceOnUse"><stop class="gp0a1qb9o"/><stop offset="1" class="y-jtnrtyv"/></radialGradient><radialGradient id="ivZDyqd" cx="0" cy="0" r="1" gradientTransform="rotate(160.412 8.903 7.742)scale(9.71985 13.8653)" gradientUnits="userSpaceOnUse"><stop offset=".889" class="wu4ue9yvv"/><stop offset="1" class="jltl75e8y"/></radialGradient><radialGradient id="i6FJcNe" cx="0" cy="0" r="1" gradientTransform="rotate(112.817 6.15 15.25)scale(5.35728 16.4557)" gradientUnits="userSpaceOnUse"><stop class="e1d1o5r5w"/><stop offset="1" class="d4q__dbfq"/></radialGradient><radialGradient id="if7berv" cx="0" cy="0" r="1" gradientTransform="matrix(-6.05883 0 0 -12.0286 21.135 16.795)" gradientUnits="userSpaceOnUse"><stop offset=".838" class="av7bm19qs"/><stop offset="1" class="hawt1inxx"/></radialGradient><radialGradient id="ikBhqgd" cx="0" cy="0" r="1" gradientTransform="matrix(22.82617 10.50104 -11.16142 24.26165 4.075 11.694)" gradientUnits="userSpaceOnUse"><stop offset=".946" class="mj1z23gjk"/><stop offset="1" class="t1vhf4i0o"/></radialGradient><radialGradient id="iX7mUwc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.73897 19.88493 -15.06185 -2.83208 18.226 10.577)" gradientUnits="userSpaceOnUse"><stop offset=".839" class="w7i1xbbya"/><stop offset="1" class="sy-7kef4t"/></radialGradient><linearGradient id="iiNpjkb" x1="12.033" x2="15.053" y1="11.551" y2="11.561" gradientUnits="userSpaceOnUse"><stop class="v3qnn2buu"/><stop offset="1" class="p9ggq2b-i"/></linearGradient><linearGradient id="iMA8nRc" x1="15.587" x2="15.217" y1="12.906" y2="12.906" gradientUnits="userSpaceOnUse"><stop class="d8ispv7tk"/><stop offset="1" class="n3li9gbai"/></linearGradient><linearGradient id="iSG5USb" x1="16.491" x2="20.928" y1="10.638" y2="10.638" gradientUnits="userSpaceOnUse"><stop class="q55eu3j3i"/><stop offset="1" class="f9dsazaqq"/></linearGradient><linearGradient id="iNvWRxb" x1="21.399" x2="18.262" y1="11.495" y2="11.495" gradientUnits="userSpaceOnUse"><stop class="fyhmny0zl"/><stop offset="1" class="mxkldwb2f"/></linearGradient><linearGradient id="idgqptd" x1="24.831" x2="21.825" y1="22.688" y2="20.179" gradientUnits="userSpaceOnUse"><stop offset=".249" class="txpmu2bwv"/><stop offset="1" class="sdkzpm_ww"/></linearGradient><linearGradient id="i877QOb" x1="18.262" x2="25.608" y1="16.241" y2="18.953" gradientUnits="userSpaceOnUse"><stop class="wfafjjx-q"/><stop offset="1" class="ej632eb0l"/></linearGradient><linearGradient id="iW8Rkye" x1="26.309" x2="23.746" y1="16.723" y2="16.723" gradientUnits="userSpaceOnUse"><stop class="dypy9lh0t"/><stop offset="1" class="y5-sir3_x"/></linearGradient><linearGradient id="inO9Nvd" x1="6.195" x2="7.023" y1="16.752" y2="16.752" gradientUnits="userSpaceOnUse"><stop class="tz1v4gb9t"/><stop offset="1" class="idjql7bxe"/></linearGradient><linearGradient id="izfrOJc" x1="10.305" x2="10.353" y1="8.258" y2="17.402" gradientUnits="userSpaceOnUse"><stop class="u0lnt9o6n"/><stop offset="1" class="eirey8tnw"/></linearGradient><filter id="iFYX6Kc" width="20.413" height="28.703" x="6.358" y="1.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.4125 0 0 0 0 0.295363 0 0 0 0 0.249219 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2510"/></filter><filter id="iWqN5Ud" width="14.875" height="9.703" x="11.709" y="13.252" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2510" stdDeviation="1"/></filter><filter id="iVroUTy" width="10.099" height="10.995" x="8.024" y="8.959" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2510" stdDeviation="1"/></filter><filter id="iQ7g6Zc" width="6.145" height="8.953" x="10.729" y="8.055" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.443137 0 0 0 0 0.313726 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2510"/></filter><filter id="iPTIPYd" width="6.082" height="11.031" x="15.596" y="6.445" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.392157 0 0 0 0 0.262745 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2510"/></filter><filter id="i5CMF5b" width="5.5" height="19.063" x="20.966" y="1.852" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2510" stdDeviation="1"/></filter><filter id="iFCSYqV" width="11.654" height="8.746" x="15.812" y="13.791" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2510" stdDeviation=".85"/></filter><filter id="i5ySEmd" width="3" height="9.736" x="8.172" y="7.074" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2510" stdDeviation=".5"/></filter><filter id="iYkSELd" width="2.851" height="5.453" x="13.001" y="10.395" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2510" stdDeviation=".5"/></filter><filter id="iCQxxJd" width="3.367" height="6.626" x="17.916" y="7.988" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2510" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:sign-of-the-horns-medium-dark" /></template>
<style>
.av7bm19qs {
  stop-color: var(--svg-color--79534f, #79534F);
  stop-opacity: 0;
}

.cxyhdjb7d {
  width: 1.367px;
  height: 4.626px;
  x: 18.916px;
  y: 8.988px;
  fill: var(--svg-color--a07a70, #A07A70);
  rx: 0.684px;
}

.d4q__dbfq {
  stop-color: var(--svg-color--6e384d, #6E384D);
}

.d8ispv7tk {
  stop-color: var(--svg-color--5f3627, #5F3627);
}

.dh-5lqd5o {
  d: path("M22.95 2.023a2.666 2.666 0 0 0-2.667 2.666v8.217H11.69V8.33a2.666 2.666 0 1 0-5.332 0v10.803c0 6.656 3.453 10.406 8.734 10.844h1.187c2.91-.291 5.907-1.329 8.157-4.547c1.89-3.047 1.648-6.09 1.457-7.876l-.02-.187a94 94 0 0 1-.258-2.826V4.689a2.666 2.666 0 0 0-2.666-2.666");
}

.dypy9lh0t {
  stop-color: var(--svg-color--9c786a, #9C786A);
}

.e1d1o5r5w {
  stop-color: var(--svg-color--9f7769, #9F7769);
}

.efzdvbdmj {
  stop-color: var(--svg-color--885462, #885462);
  stop-opacity: 0;
}

.eirey8tnw {
  stop-color: var(--svg-color--9e7c70, #9E7C70);
  stop-opacity: 0;
}

.ej632eb0l {
  stop-color: var(--svg-color--a57f75, #A57F75);
  stop-opacity: 0;
}

.f9dsazaqq {
  stop-color: var(--svg-color--956c59, #956C59);
}

.ft5dv1b6b {
  fill: none;
}

.fyhmny0zl {
  stop-color: var(--svg-color--9f7868, #9F7868);
}

.g72v-pb2v {
  stop-color: var(--svg-color--977567, #977567);
  stop-opacity: 0;
}

.gdb0rzbwv {
  stop-color: var(--svg-color--946e6e, #946E6E);
}

.gp0a1qb9o {
  stop-color: var(--svg-color--6a384e, #6A384E);
}

.gtukhc44n {
  width: 5.395px;
  height: 8.203px;
  x: 10.729px;
  y: 8.805px;
  rx: 2.697px;
}

.hawt1inxx {
  stop-color: var(--svg-color--79534f, #79534F);
}

.hjc9debbp {
  stop-color: var(--svg-color--977567, #977567);
}

.i7m21ubvj {
  stop-color: var(--svg-color--724d49, #724D49);
  stop-opacity: 0;
}

.idjql7bxe {
  stop-color: var(--svg-color--835e56, #835E56);
  stop-opacity: 0;
}

.irxw1xqtj {
  stop-color: var(--svg-color--724d49, #724D49);
}

.jltl75e8y {
  stop-color: var(--svg-color--7d5752, #7D5752);
}

.kx20wlbbb {
  stop-color: var(--svg-color--553225, #553225);
}

.lfcqr7rkc {
  stop-color: var(--svg-color--553225, #553225);
  stop-opacity: 0;
}

.miadccb6q {
  width: 0.851px;
  height: 3.453px;
  x: 14.001px;
  y: 11.395px;
  fill: var(--svg-color--99786f, #99786F);
  rx: 0.426px;
}

.mj1z23gjk {
  stop-color: var(--svg-color--906262, #906262);
  stop-opacity: 0;
}

.moh1otbcy {
  fill: var(--svg-color--59323b, #59323B);
  d: path("M10.024 10.959h6.099v6.995h-6.099z");
}

.mxkldwb2f {
  stop-color: var(--svg-color--9f7868, #9F7868);
  stop-opacity: 0;
}

.n1h42xbld {
  width: 5.332px;
  height: 10.281px;
  x: 15.596px;
  y: 7.195px;
  rx: 2.666px;
}

.n3li9gbai {
  stop-color: var(--svg-color--5f3627, #5F3627);
  stop-opacity: 0;
}

.ntmgj10ki {
  d: path("M22.95 2.023a2.666 2.666 0 0 0-2.667 2.666v3.434c.402.467.645 1.074.645 1.738v4.95a2.666 2.666 0 0 1-5.184.879a2.697 2.697 0 0 1-5.016-1.38v-2.808c0-.828.374-1.57.962-2.064V8.33a2.666 2.666 0 1 0-5.332 0v10.803c0 6.656 3.453 10.406 8.734 10.844h1.187c2.91-.291 5.907-1.329 8.157-4.547c1.89-3.047 1.648-6.09 1.457-7.876l-.02-.187a94 94 0 0 1-.258-2.826V4.689a2.666 2.666 0 0 0-2.666-2.666");
}

.ohdcwacvr {
  d: path("M17.928 14.117h1.68Z");
}

.p9ggq2b-i {
  stop-color: var(--svg-color--8d6958, #8D6958);
}

.pvnortbhk {
  width: 5.332px;
  height: 15.453px;
  x: 20.283px;
  y: 2.023px;
  rx: 2.666px;
}

.pwlhh4byl {
  width: 5.332px;
  height: 11.813px;
  x: 6.358px;
  y: 5.664px;
  rx: 2.666px;
}

.q_7t6qbvi {
  d: path("M17.928 14.117a2.852 2.852 0 1 0 0 5.703h1.624a1 1 0 0 1 .743.441l2.471 3.652a1 1 0 0 0 1.745-.16l.937-2.142c.332-.759.543-1.586.38-2.398a6.346 6.346 0 0 0-6.213-5.096");
}

.q55eu3j3i {
  stop-color: var(--svg-color--7a574a, #7A574A);
}

.qas3z0pzv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18.262 16.241h2.834a3 3 0 0 1 2.613 1.527l1.307 2.319");
}

.r02rrubfh {
  stop-color: var(--svg-color--52292d, #52292D);
}

.rpzexvboz {
  stop-color: var(--svg-color--9e7b6f, #9E7B6F);
}

.rspk5kbip {
  stroke: var(--svg-color--9c776c, #9C776C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M23.716 4.602v13.562");
}

.s-ksbeban {
  stop-color: var(--svg-color--52292d, #52292D);
  stop-opacity: 0;
}

.sdkzpm_ww {
  stop-color: var(--svg-color--8c5f5d, #8C5F5D);
  stop-opacity: 0;
}

.sy-7kef4t {
  stop-color: var(--svg-color--7b406c, #7B406C);
}

.t1vhf4i0o {
  stop-color: var(--svg-color--906262, #906262);
}

.t6m8ihbxo {
  stroke-linecap: round;
  d: path("M9.672 8.574v6.737");
}

.txpmu2bwv {
  stop-color: var(--svg-color--8c5f5d, #8C5F5D);
}

.tz1v4gb9t {
  stop-color: var(--svg-color--835e56, #835E56);
}

.u0lnt9o6n {
  stop-color: var(--svg-color--9e7c70, #9E7C70);
}

.uecs0-bwr {
  stop-color: var(--svg-color--885462, #885462);
}

.v3qnn2buu {
  stop-color: var(--svg-color--785146, #785146);
}

.vg9i9_2xu {
  d: path("M16.56 15.252a2.852 2.852 0 1 0 0 5.703h1.625c3.034 0 4.127 0 6.399-.256c0-3.5-2.836-5.443-6.336-5.447m-1.688 0h1.68Z");
}

.w7i1xbbya {
  stop-color: var(--svg-color--7b406c, #7B406C);
  stop-opacity: 0;
}

.wfafjjx-q {
  stop-color: var(--svg-color--a57f75, #A57F75);
}

.wk1gub3hc {
  fill: var(--svg-color--59323b, #59323B);
}

.wu4ue9yvv {
  stop-color: var(--svg-color--7d5752, #7D5752);
  stop-opacity: 0;
}

.xa6cjn3la {
  stop-color: var(--svg-color--a37f71, #A37F71);
  stop-opacity: 0;
}

.xey_m__0s {
  stop-color: var(--svg-color--946e6e, #946E6E);
  stop-opacity: 0;
}

.xjwesibys {
  stop-color: var(--svg-color--a37f71, #A37F71);
}

.xp1mkrtwj {
  fill: var(--svg-color--926362, #926362);
  d: path("M22.95 2.023a2.666 2.666 0 0 0-2.667 2.666v8.217H11.69V8.33a2.666 2.666 0 1 0-5.332 0v10.803c0 6.656 3.453 10.406 8.734 10.844h1.187c2.91-.291 5.907-1.329 8.157-4.547c1.89-3.047 1.648-6.09 1.457-7.876l-.02-.187a94 94 0 0 1-.258-2.826V4.689a2.666 2.666 0 0 0-2.666-2.666");
}

.y-jtnrtyv {
  stop-color: var(--svg-color--6a384e, #6A384E);
  stop-opacity: 0;
}

.y5-sir3_x {
  stop-color: var(--svg-color--9c786a, #9C786A);
  stop-opacity: 0;
}

.yogzn9brn {
  stop-color: var(--svg-color--9e7b6f, #9E7B6F);
  stop-opacity: 0;
}

</style>
