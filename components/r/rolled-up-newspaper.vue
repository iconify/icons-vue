<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iVLjqec)"><path fill="url(#i4NfdJe)" class="zy37t084g"/></g><g filter="url(#iCeLftb)"><path fill="url(#iuLXeOs)" class="v_o5vcrji"/></g><g filter="url(#icLk1Oe)"><path fill="url(#ijUN8yc)" class="drtukfbtj"/></g><path class="vlyckkbqu"/><path fill="url(#ikeGk9d)" class="ygsmrlbwc"/><path fill="url(#iSqjmrd)" class="ygsmrlbwc"/><g filter="url(#itV62Ld)"><path fill="url(#iTMHJNb)" class="q4ffv6tvm"/><path fill="url(#ii6Hvad)" class="q4ffv6tvm"/></g><g filter="url(#iGDX0Db)"><path class="q3m1_abqn"/><path fill="url(#iRvHhae)" class="i55c-nbne"/><path fill="url(#iisHCye)" class="i55c-nbne"/></g><path stroke="url(#iyC7Lcb)" class="rkvrmwd8t"/><path stroke="url(#iZGgtmd)" class="rw2nocbpm"/><path stroke="url(#iimGq9b)" class="y3kamrbrx"/><path fill="url(#isAhSEd)" class="bqzvnub9y"/><g filter="url(#iowgvgc)"><path class="uiyb--bra"/><path fill="url(#i6zbDkR)" class="atmpiwbuq"/><path fill="url(#iDvpCAe)" class="atmpiwbuq"/></g><path class="x5djf2bjo"/><path fill="url(#iDjXZMc)" class="p5fr9vp2u"/><path fill="url(#iK0RFFe)" class="p5fr9vp2u"/><path fill="url(#irQMQfe)" class="p5fr9vp2u"/><g filter="url(#ialleuc)"><path stroke="url(#iNxfogb)" class="ciwcxxbxq"/></g><defs><radialGradient id="i4NfdJe" cx="0" cy="0" r="1" gradientTransform="matrix(-5.59376 1.82573 -1.86797 -5.7232 9.283 23.855)" gradientUnits="userSpaceOnUse"><stop offset=".746" class="y-98-xrix"/><stop offset="1" class="fjmzxdicl"/></radialGradient><radialGradient id="iuLXeOs" cx="0" cy="0" r="1" gradientTransform="rotate(154.73 1.645 12.58)scale(5.56364 5.87643)" gradientUnits="userSpaceOnUse"><stop offset=".796" class="y-98-xrix"/><stop offset="1" class="fjmzxdicl"/></radialGradient><radialGradient id="ijUN8yc" cx="0" cy="0" r="1" gradientTransform="rotate(154.879 2.51 12.222)scale(6.24037 6.84519)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="w1dwncb6p"/><stop offset="1" class="psmdepm3q"/></radialGradient><radialGradient id="iSqjmrd" cx="0" cy="0" r="1" gradientTransform="rotate(-139.912 7.868 10.693)scale(5.6777 4.35703)" gradientUnits="userSpaceOnUse"><stop offset=".805" class="tcextcbnt"/><stop offset="1" class="af9jp5bim"/></radialGradient><radialGradient id="i6zbDkR" cx="0" cy="0" r="1" gradientTransform="rotate(147.95 .945 12.908)scale(4.23999 4.79369)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="d-7bbabdc"/><stop offset="1" class="nvldbybtz"/></radialGradient><radialGradient id="iDvpCAe" cx="0" cy="0" r="1" gradientTransform="rotate(-38.304 39.94 4.49)scale(5.49547 5.4486)" gradientUnits="userSpaceOnUse"><stop offset=".816" class="y47jyn_xw"/><stop offset=".993" class="bi2n6dbte"/></radialGradient><radialGradient id="iDjXZMc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.4375 .84375 -.58728 -1.00055 6.596 23.035)" gradientUnits="userSpaceOnUse"><stop offset=".475" class="ugjpqxbab"/><stop offset="1" class="qkdy6ccoe"/></radialGradient><radialGradient id="iK0RFFe" cx="0" cy="0" r="1" gradientTransform="matrix(3.06248 -3.15627 3.71103 3.60076 7.252 25.222)" gradientUnits="userSpaceOnUse"><stop offset=".645" class="pe8__9b4m"/><stop offset=".926" class="gck472bfo"/></radialGradient><radialGradient id="irQMQfe" cx="0" cy="0" r="1" gradientTransform="matrix(1.63769 -1.3594 1.26899 1.52878 7.818 27.785)" gradientUnits="userSpaceOnUse"><stop offset=".309" class="pm5h0vjiy"/><stop offset="1" class="nslgz0v9n"/></radialGradient><radialGradient id="iNxfogb" cx="0" cy="0" r="1" gradientTransform="rotate(98.039 -5.48 14.626)scale(4.82871 6.05431)" gradientUnits="userSpaceOnUse"><stop class="p4qx8x-3j"/><stop offset=".778" class="cm7qvcbwp"/></radialGradient><linearGradient id="ikeGk9d" x1="14.908" x2="9.971" y1="18.878" y2="13.847" gradientUnits="userSpaceOnUse"><stop offset=".562" class="g7n6gwq8e"/><stop offset="1" class="afo-t3bjz"/></linearGradient><linearGradient id="iTMHJNb" x1="11.687" x2="26.408" y1="15.945" y2="1.756" gradientUnits="userSpaceOnUse"><stop class="h3359vbpt"/><stop offset="1" class="h4gtjubji"/></linearGradient><linearGradient id="ii6Hvad" x1="19.565" x2="17.096" y1="10.66" y2="8.066" gradientUnits="userSpaceOnUse"><stop offset=".441" class="y7oj0_buf"/><stop offset="1" class="o2bli3buh"/></linearGradient><linearGradient id="iRvHhae" x1="21.315" x2="18.752" y1="19.972" y2="17.41" gradientUnits="userSpaceOnUse"><stop class="fb4tksb3c"/><stop offset="1" class="xzjucrbnr"/></linearGradient><linearGradient id="iisHCye" x1="14.627" x2="17.44" y1="10.535" y2="13.347" gradientUnits="userSpaceOnUse"><stop class="pplnvv__n"/><stop offset="1" class="xk-by4b4y"/></linearGradient><linearGradient id="iyC7Lcb" x1="16.572" x2="18.002" y1="16.285" y2="20.972" gradientUnits="userSpaceOnUse"><stop class="j0t9_sbsv"/><stop offset="1" class="hwpblnb9t"/></linearGradient><linearGradient id="iZGgtmd" x1="25.26" x2="26.544" y1="7.513" y2="12.172" gradientUnits="userSpaceOnUse"><stop class="j0t9_sbsv"/><stop offset="1" class="hwpblnb9t"/></linearGradient><linearGradient id="iimGq9b" x1="26.955" x2="28.182" y1="5.731" y2="10.319" gradientUnits="userSpaceOnUse"><stop class="j0t9_sbsv"/><stop offset="1" class="hwpblnb9t"/></linearGradient><linearGradient id="isAhSEd" x1="19.877" x2="22.815" y1="12.41" y2="16.285" gradientUnits="userSpaceOnUse"><stop class="jgwx3-koq"/><stop offset="1" class="zvmydd0jc"/></linearGradient><filter id="iVLjqec" width="11.578" height="11.203" x="2.236" y="18.253" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.717647 0 0 0 0 0.623529 0 0 0 0 0.807843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_21204"/></filter><filter id="iCeLftb" width="9.663" height="10.156" x="2.995" y="18.175" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.596078 0 0 0 0 0.752941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_21204"/></filter><filter id="icLk1Oe" width="8.278" height="9.156" x="3.938" y="18.019" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.709804 0 0 0 0 0.639216 0 0 0 0 0.784314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_21204"/></filter><filter id="itV62Ld" width="19.144" height="27.591" x="7.264" y="1.756" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.713726 0 0 0 0 0.701961 0 0 0 0 0.733333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_21204"/></filter><filter id="iGDX0Db" width="20.736" height="27.614" x="9.362" y="1.733" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.796078 0 0 0 0 0.823529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_21204"/></filter><filter id="iowgvgc" width="8.445" height="8.265" x="3.729" y="19.894" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.72549 0 0 0 0 0.654902 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_21204"/></filter><filter id="ialleuc" width="5.445" height="5.716" x="4.841" y="21.431" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_21204" stdDeviation=".1"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:rolled-up-newspaper" /></template>
<style>
.af9jp5bim {
  stop-color: var(--svg-color--beacd1, #BEACD1);
  stop-opacity: 0;
}

.afo-t3bjz {
  stop-color: var(--svg-color--a69ab4, #A69AB4);
  stop-opacity: 0;
}

.atmpiwbuq {
  d: path("M4.308 25.316c-1.412-2.388.089-4.484 1.016-5.234c1.453-.485 3.19 0 4.578 1.109c2.062 1.648 2.383 4.242 1.695 5.336c-.55.875-1.846 1.482-2.414 1.633c1.606-1.22 1.575-2.429 1.631-3.185c-.056.438-.346 1.136-.99 1.638c-.703.547-3.75 1.687-5.516-1.297");
}

.bi2n6dbte {
  stop-color: var(--svg-color--a694b9, #A694B9);
}

.bqzvnub9y {
  d: path("m20.521 7.966l-4.4 4.318c-.209.204-.135.558.13.681a7.22 7.22 0 0 1 4.029 4.912c.078.328.5.47.736.23l4.226-4.28a.4.4 0 0 0 .113-.293c-.177-3.88-2.723-5.381-4.507-5.675a.38.38 0 0 0-.327.107");
}

.ciwcxxbxq {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M5.111 23.19c.167-.442.79-1.484 1.985-1.484c1.219 0 2.341.752 2.781 2.25c.5 1.704-.516 2.641-1.172 2.922");
}

.cm7qvcbwp {
  stop-color: var(--svg-color--bca9cf, #BCA9CF);
  stop-opacity: 0;
}

.d-7bbabdc {
  stop-color: var(--svg-color--645d6c, #645D6C);
}

.drtukfbtj {
  d: path("M11.688 22.603c0 2.508-1.422 4.494-3.532 4.572c-2.03 0-4.358-1.292-4.212-4.572c.102-2.293 3.215-4.084 5.665-4.084c2.509 0 2.079 1.576 2.079 4.084");
}

.fb4tksb3c {
  stop-color: var(--svg-color--cfc4db, #CFC4DB);
}

.fjmzxdicl {
  stop-color: var(--svg-color--c5b4d7, #C5B4D7);
}

.ft5dv1b6b {
  fill: none;
}

.g7n6gwq8e {
  stop-color: var(--svg-color--a69ab4, #A69AB4);
}

.gck472bfo {
  stop-color: var(--svg-color--a290b4, #A290B4);
}

.h3359vbpt {
  stop-color: var(--svg-color--c5becc, #C5BECC);
}

.h4gtjubji {
  stop-color: var(--svg-color--c0bcc5, #C0BCC5);
}

.hwpblnb9t {
  stop-color: var(--svg-color--908c95, #908C95);
}

.i55c-nbne {
  d: path("M12.752 28.203c-1.07.938-2.802 1.242-3.312 1.117c5.838-1.735 3.485-7.573.28-10.622c-.44-.418-.49-1.128-.06-1.557L24.55 2.295c.51-.51 1.247-.746 1.876-.394c1.09.61 2.544 1.918 3.28 4.24c1.023 3.222-.163 5.102-1.11 6.062c-4.79 4.865-14.62 14.928-15.843 16");
}

.j0t9_sbsv {
  stop-color: var(--svg-color--aaa7ae, #AAA7AE);
}

.jgwx3-koq {
  stop-color: var(--svg-color--b9b7bd, #B9B7BD);
}

.nslgz0v9n {
  stop-color: var(--svg-color--9b8aad, #9B8AAD);
  stop-opacity: 0;
}

.nvldbybtz {
  stop-color: var(--svg-color--645d6c, #645D6C);
  stop-opacity: 0;
}

.o2bli3buh {
  stop-color: var(--svg-color--c0bac6, #C0BAC6);
  stop-opacity: 0;
}

.p4qx8x-3j {
  stop-color: var(--svg-color--bca9cf, #BCA9CF);
}

.p5fr9vp2u {
  d: path("M5.574 23.37c.418-.262 1.169-1.078 1.492-1.453c.75 0 1.396.378 1.812.813c1.04.96.977 2.172.711 2.781c-.314.722-1.14 1.3-1.703 1.43l.078.36c1.098-.102 2.54-.704 2.813-1.993c.23-1.084-.28-2.572-1.782-3.727a3.4 3.4 0 0 0-2.67-.689a.78.78 0 0 0-.465.263c-.509.59-1.024 1.46-1.052 1.848c-.031.438.242.696.766.368");
}

.pe8__9b4m {
  stop-color: var(--svg-color--a290b4, #A290B4);
  stop-opacity: 0;
}

.pm5h0vjiy {
  stop-color: var(--svg-color--9b8aad, #9B8AAD);
}

.pplnvv__n {
  stop-color: var(--svg-color--dbd5e2, #DBD5E2);
}

.psmdepm3q {
  stop-color: var(--svg-color--b3a4c3, #B3A4C3);
}

.q3m1_abqn {
  fill: var(--svg-color--f8f4fc, #F8F4FC);
  d: path("M12.752 28.203c-1.07.938-2.802 1.242-3.312 1.117c5.838-1.735 3.485-7.573.28-10.622c-.44-.418-.49-1.128-.06-1.557L24.55 2.295c.51-.51 1.247-.746 1.876-.394c1.09.61 2.544 1.918 3.28 4.24c1.023 3.222-.163 5.102-1.11 6.062c-4.79 4.865-14.62 14.928-15.843 16");
}

.q4ffv6tvm {
  d: path("M9.753 29.282q-.131.045-.25.065q.125-.03.25-.065c1.262-.441 3.233-2.67 2.874-4.966c-.543-3.468-3.111-5.232-4.96-6.108c-.424-.2-.543-.765-.212-1.097l14.543-14.57c.563-.564 1.334-.906 2.114-.745c.786.164 1.647.482 2.296 1.004L12.815 20.91c.354.802 1 2.85.75 4.625c-.3 2.127-1.892 3.22-3.812 3.747");
}

.qkdy6ccoe {
  stop-color: var(--svg-color--7f738b, #7F738B);
  stop-opacity: 0;
}

.rkvrmwd8t {
  stroke-linecap: round;
  d: path("M14.674 14.582c1.156.484 3.375 2.312 3.797 5.78");
}

.rw2nocbpm {
  stroke-linecap: round;
  d: path("M23.205 5.847c1.36.5 3.625 1.828 4.11 5.656");
}

.tcextcbnt {
  stop-color: var(--svg-color--beacd1, #BEACD1);
}

.ugjpqxbab {
  stop-color: var(--svg-color--7f738b, #7F738B);
}

.uiyb--bra {
  fill: var(--svg-color--a895bc, #A895BC);
  d: path("M4.308 25.316c-1.412-2.388.089-4.484 1.016-5.234c1.453-.485 3.19 0 4.578 1.109c2.062 1.648 2.383 4.242 1.695 5.336c-.55.875-1.846 1.482-2.414 1.633c1.606-1.22 1.575-2.429 1.631-3.185c-.056.438-.346 1.136-.99 1.638c-.703.547-3.75 1.687-5.516-1.297");
}

.v_o5vcrji {
  d: path("M12.658 23.05c0 2.684-2.035 5.281-4.718 5.281c-2.684 0-5.094-2.13-4.938-5.64c.11-2.453 2.507-4.516 5.13-4.516c2.683 0 4.526 2.191 4.526 4.875");
}

.vlyckkbqu {
  fill: var(--svg-color--bdb7c5, #BDB7C5);
  d: path("M9.664 29.294q-.1.046-.193.069q.098-.033.193-.069c.994-.457 2.436-2.63 2.026-4.884c-.776-4.267-5.625-5.704-8.688-3.516c.125-.208.513-.76 1.063-1.297S14.71 8.873 19.69 3.847c.453-.469 1.659-1.362 2.859-1.187l-5.453 18.234c-.657 2.15-3.055 6.795-7.432 8.4");
}

.w1dwncb6p {
  stop-color: var(--svg-color--645e6c, #645E6C);
}

.x5djf2bjo {
  fill: var(--svg-color--ae9ac2, #AE9AC2);
  d: path("M5.574 23.37c.418-.262 1.169-1.078 1.492-1.453c.75 0 1.396.378 1.812.813c1.04.96.977 2.172.711 2.781c-.314.722-1.14 1.3-1.703 1.43l.078.36c1.098-.102 2.54-.704 2.813-1.993c.23-1.084-.28-2.572-1.782-3.727a3.4 3.4 0 0 0-2.67-.689a.78.78 0 0 0-.465.263c-.509.59-1.024 1.46-1.052 1.848c-.031.438.242.696.766.368");
}

.xk-by4b4y {
  stop-color: var(--svg-color--dbd5e2, #DBD5E2);
  stop-opacity: 0;
}

.xzjucrbnr {
  stop-color: var(--svg-color--cfc4db, #CFC4DB);
  stop-opacity: 0;
}

.y-98-xrix {
  stop-color: var(--svg-color--9b8bab, #9B8BAB);
}

.y3kamrbrx {
  stroke-linecap: round;
  d: path("M24.877 4.097c1.36.5 3.516 1.703 4.156 5.547");
}

.y47jyn_xw {
  stop-color: var(--svg-color--a694b9, #A694B9);
  stop-opacity: 0;
}

.y7oj0_buf {
  stop-color: var(--svg-color--c0bac6, #C0BAC6);
}

.ygsmrlbwc {
  d: path("M9.664 29.294q-.1.046-.193.069q.098-.033.193-.069c.994-.457 2.436-2.63 2.026-4.884c-.776-4.267-5.625-5.704-8.688-3.516c.125-.208.513-.76 1.063-1.297S14.71 8.873 19.69 3.847c.453-.469 1.659-1.362 2.859-1.187l-5.453 18.234c-.657 2.15-3.055 6.795-7.432 8.4");
}

.zvmydd0jc {
  stop-color: var(--svg-color--a5a1aa, #A5A1AA);
}

.zy37t084g {
  d: path("M13.815 23.855c0 3.094-2.522 5.601-5.633 5.601s-5.946-2.904-5.946-5.997s2.907-5.206 5.946-5.206c3.11 0 5.633 2.508 5.633 5.602");
}

</style>
