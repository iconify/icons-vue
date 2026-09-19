<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iVmfIiz)"><path class="dnegmx6hi"/><path fill="url(#iJgPQtd)" class="fqe7ixbng"/><path fill="url(#iTJjtnd)" class="fqe7ixbng"/></g><path fill="url(#ijzkt7d)" class="la18v8bdt"/><g filter="url(#iAGjWZH)"><path fill="url(#iWAt6FV)" class="yafcvbc6z"/></g><path fill="url(#igp31Ob)" class="oq92pq7ha"/><path fill="url(#iB78Noj)" class="oq92pq7ha"/><path fill="url(#i10nWMX)" class="oq92pq7ha"/><path fill="url(#iLH5mDe)" class="oq92pq7ha"/><path fill="url(#iYG56pb)" class="oq92pq7ha"/><g filter="url(#iVQE1Fe)"><path class="g62rx8b1e"/></g><path fill="url(#ix1vjee)" class="va8v2kriz"/><path fill="url(#iyYm2Pb)" class="va8v2kriz"/><path fill="url(#i05vugd)" class="va8v2kriz"/><path fill="url(#ibwK0uc)" class="va8v2kriz"/><g filter="url(#iKqZn5d)"><path fill="url(#iiMwxue)" class="pc_ypn7fw"/></g><path fill="url(#ifhwMQe)" class="jrl5b5bpz"/><path fill="url(#iTL7Rgb)" class="jrl5b5bpz"/><path fill="url(#iMfw80c)" class="jrl5b5bpz"/><path fill="url(#iwUYJ6b)" class="jrl5b5bpz"/><g filter="url(#iuHkKCQ)"><path fill="url(#iXzX63b)" class="ey86uh85b"/></g><path fill="url(#iX4Apkd)" class="fqe7ixbng"/><path fill="url(#i2HuuWd)" class="fqe7ixbng"/><path fill="url(#i5Cp5wX)" class="fqe7ixbng"/><path fill="url(#iQcv00O)" class="fqe7ixbng"/><path fill="url(#i9H2MOG)" class="fqe7ixbng"/><path fill="url(#iQTve7d)" class="fqe7ixbng"/><g filter="url(#iDdy4yc)"><path fill="url(#iBI709d)" class="p3kpdx-jh"/></g><path fill="url(#ipduSId)" class="t2y--rbpl"/><path fill="url(#i1X3tad)" class="t2y--rbpl"/><path fill="url(#iYPKche)" class="t2y--rbpl"/><g filter="url(#iGAPfob)"><path fill="url(#iU1ceXd)" class="e88yeyaxk"/></g><defs><linearGradient id="iWAt6FV" x1="6.372" x2="10.681" y1="13.586" y2="20.376" gradientUnits="userSpaceOnUse"><stop class="x9sp0lxpb"/><stop offset="1" class="mta-gxbha"/></linearGradient><linearGradient id="igp31Ob" x1="8.999" x2="11.049" y1="11.845" y2="11.733" gradientUnits="userSpaceOnUse"><stop class="nvhcxvb-x"/><stop offset="1" class="o602s3q4k"/></linearGradient><linearGradient id="iB78Noj" x1="14.023" x2="13.039" y1="11.061" y2="11.076" gradientUnits="userSpaceOnUse"><stop class="n9j7mnb6l"/><stop offset="1" class="ca0jfjbzt"/></linearGradient><linearGradient id="iLH5mDe" x1="11.47" x2="10.851" y1="16.779" y2="14.779" gradientUnits="userSpaceOnUse"><stop offset=".236" class="hdbhm0bnq"/><stop offset="1" class="ojod5htzj"/></linearGradient><linearGradient id="ix1vjee" x1="12.695" x2="15.774" y1="9.889" y2="9.836" gradientUnits="userSpaceOnUse"><stop class="sqmhaybyy"/><stop offset="1" class="k3lbqdbda"/></linearGradient><linearGradient id="i05vugd" x1="18.877" x2="17.669" y1="9.515" y2="9.515" gradientUnits="userSpaceOnUse"><stop class="j84_0ishg"/><stop offset="1" class="zp9vxoqbl"/></linearGradient><linearGradient id="ibwK0uc" x1="15.226" x2="15.431" y1="17.076" y2="14.145" gradientUnits="userSpaceOnUse"><stop class="hdbhm0bnq"/><stop offset="1" class="ojod5htzj"/></linearGradient><linearGradient id="iiMwxue" x1="17.53" x2="26.161" y1="2.156" y2="8.318" gradientUnits="userSpaceOnUse"><stop class="wph0opaub"/><stop offset="1" class="cvo9a4s4m"/></linearGradient><linearGradient id="ifhwMQe" x1="17.598" x2="20.382" y1="10.823" y2="10.771" gradientUnits="userSpaceOnUse"><stop class="i04f7joye"/><stop offset="1" class="c7c1ompfs"/></linearGradient><linearGradient id="iTL7Rgb" x1="23.511" x2="22.04" y1="10.851" y2="10.861" gradientUnits="userSpaceOnUse"><stop class="n5ewo8byt"/><stop offset="1" class="i1zhfgnpn"/></linearGradient><linearGradient id="iMfw80c" x1="19.414" x2="19.943" y1="15.889" y2="13.15" gradientUnits="userSpaceOnUse"><stop class="hdbhm0bnq"/><stop offset="1" class="ojod5htzj"/></linearGradient><linearGradient id="iXzX63b" x1="21.803" x2="21.803" y1="5.451" y2="19.014" gradientUnits="userSpaceOnUse"><stop class="t1pbx2bxi"/><stop offset="1" class="jgwlmcmzo"/></linearGradient><linearGradient id="iX4Apkd" x1="27.313" x2="21.959" y1="22.599" y2="22.599" gradientUnits="userSpaceOnUse"><stop class="bpzk7poxj"/><stop offset="1" class="bcg91z1pi"/></linearGradient><linearGradient id="iBI709d" x1="27.154" x2="24.185" y1="16.131" y2="16.025" gradientUnits="userSpaceOnUse"><stop class="xbduuqv3a"/><stop offset="1" class="s-2xfac7e"/></linearGradient><linearGradient id="ipduSId" x1="21.684" x2="24.011" y1="12.609" y2="12.855" gradientUnits="userSpaceOnUse"><stop class="k-0lcabla"/><stop offset="1" class="p0wx8vbfh"/></linearGradient><linearGradient id="i1X3tad" x1="24.011" x2="24.113" y1="16.951" y2="14.404" gradientUnits="userSpaceOnUse"><stop class="kxe70_b8r"/><stop offset="1" class="udexd28np"/></linearGradient><linearGradient id="iU1ceXd" x1="25.984" x2="25.735" y1="8.524" y2="22.084" gradientUnits="userSpaceOnUse"><stop class="i94u7374x"/><stop offset="1" class="oa5qxrb6u"/></linearGradient><radialGradient id="iJgPQtd" cx="0" cy="0" r="1" gradientTransform="matrix(5.125 -2.625 9.42008 18.39159 9.445 27.076)" gradientUnits="userSpaceOnUse"><stop class="c8rwtvj3l"/><stop offset="1" class="uyel8mbjo"/></radialGradient><radialGradient id="iTJjtnd" cx="0" cy="0" r="1" gradientTransform="matrix(.4595 2.43885 -3.85022 .7254 5.843 12.077)" gradientUnits="userSpaceOnUse"><stop class="oxcebbo2u"/><stop offset="1" class="l8nkzzbwc"/></radialGradient><radialGradient id="ijzkt7d" cx="0" cy="0" r="1" gradientTransform="rotate(146.31 2.712 9.22)scale(1.33802 3.89834)" gradientUnits="userSpaceOnUse"><stop class="e5wz7zbbf"/><stop offset="1" class="s1g--acyf"/></radialGradient><radialGradient id="i10nWMX" cx="0" cy="0" r="1" gradientTransform="rotate(157.319 6.42 3.993)scale(1.13462 1.78724)" gradientUnits="userSpaceOnUse"><stop class="ql9m72tpr"/><stop offset="1" class="wko5rrbnp"/></radialGradient><radialGradient id="iYG56pb" cx="0" cy="0" r="1" gradientTransform="matrix(.97056 1.68398 -3.94738 2.27506 10.008 3.795)" gradientUnits="userSpaceOnUse"><stop class="azqf21bvt"/><stop offset="1" class="op60lab0l"/></radialGradient><radialGradient id="iyYm2Pb" cx="0" cy="0" r="1" gradientTransform="matrix(.87499 1.62144 -2.44595 1.31993 14.601 2.017)" gradientUnits="userSpaceOnUse"><stop class="itzhybc5e"/><stop offset="1" class="o7wbjjbaq"/></radialGradient><radialGradient id="iwUYJ6b" cx="0" cy="0" r="1" gradientTransform="matrix(.79135 1.354 -2.12907 1.24435 19.322 4.25)" gradientUnits="userSpaceOnUse"><stop class="g_aaj6gld"/><stop offset="1" class="jvw4ebt-r"/></radialGradient><radialGradient id="i2HuuWd" cx="0" cy="0" r="1" gradientTransform="matrix(-.1875 -2.2675 1.77572 -.14684 12.664 16)" gradientUnits="userSpaceOnUse"><stop class="jhesu-hxj"/><stop offset="1" class="sne-vkbdr"/></radialGradient><radialGradient id="i5Cp5wX" cx="0" cy="0" r="1" gradientTransform="matrix(-.09377 -2.17374 2.00449 -.08647 17.383 16)" gradientUnits="userSpaceOnUse"><stop class="jhesu-hxj"/><stop offset="1" class="sne-vkbdr"/></radialGradient><radialGradient id="iQcv00O" cx="0" cy="0" r="1" gradientTransform="rotate(-91.909 18.479 -2.164)scale(1.87604)" gradientUnits="userSpaceOnUse"><stop class="jhesu-hxj"/><stop offset="1" class="sne-vkbdr"/></radialGradient><radialGradient id="i9H2MOG" cx="0" cy="0" r="1" gradientTransform="matrix(-2.125 -1.06245 1.39986 -2.79985 24.789 16.484)" gradientUnits="userSpaceOnUse"><stop class="jhesu-hxj"/><stop offset="1" class="sne-vkbdr"/></radialGradient><radialGradient id="iQTve7d" cx="0" cy="0" r="1" gradientTransform="rotate(-27.758 49.749 -5.793)scale(3.03562 12.0503)" gradientUnits="userSpaceOnUse"><stop class="hcnm0gbnl"/><stop offset="1" class="ys91hqkls"/></radialGradient><radialGradient id="iYPKche" cx="0" cy="0" r="1" gradientTransform="matrix(.84085 1.7617 -4.7063 2.2463 23.383 6.639)" gradientUnits="userSpaceOnUse"><stop class="uj-6nfb_i"/><stop offset="1" class="xdyu8nbjh"/></radialGradient><filter id="iVmfIiz" width="23.289" height="28.965" x="3.888" y="1.017" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-1"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.34902 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_1269"/></filter><filter id="iAGjWZH" width="5.458" height="7.823" x="4.872" y="12.345" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1269" stdDeviation=".375"/></filter><filter id="iVQE1Fe" width="3.414" height="12.102" x="10.68" y="4.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1269" stdDeviation=".5"/></filter><filter id="iKqZn5d" width="4.064" height="15.808" x="14.813" y="1.754" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1269" stdDeviation=".5"/></filter><filter id="iuHkKCQ" width="3.555" height="13.094" x="19.593" y="4.451" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1269" stdDeviation=".5"/></filter><filter id="iDdy4yc" width="6.11" height="21.827" x="21.436" y="6.755" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1269" stdDeviation=".5"/></filter><filter id="iGAPfob" width="3.521" height="13.092" x="23.749" y="7.516" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1269" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:raised-back-of-hand-medium" /></template>
<style>
.azqf21bvt {
  stop-color: var(--svg-color--a2846c, #A2846C);
}

.bcg91z1pi {
  stop-color: var(--svg-color--c59b81, #C59B81);
  stop-opacity: 0;
}

.bpzk7poxj {
  stop-color: var(--svg-color--c59b81, #C59B81);
}

.c7c1ompfs {
  stop-color: var(--svg-color--8d5e4f, #8D5E4F);
  stop-opacity: 0;
}

.c8rwtvj3l {
  stop-color: var(--svg-color--926563, #926563);
}

.ca0jfjbzt {
  stop-color: var(--svg-color--855d50, #855D50);
  stop-opacity: 0;
}

.cvo9a4s4m {
  stop-color: var(--svg-color--c79e8a, #C79E8A);
  stop-opacity: 0;
}

.dnegmx6hi {
  fill: var(--svg-color--b3857a, #B3857A);
  d: path("M13.562 4.49a2.406 2.406 0 0 1 4.81-.135l.026.945a2.406 2.406 0 0 1 4.393 1.4l-.026 1.37a2.406 2.406 0 0 1 4.16 1.736l-.335 8.822c-.005 1.33-.15 3.695-1.004 5.76c-1.208 3.267-4.34 5.595-8.016 5.595c-3.715 0-6.876-2.379-8.055-5.701c-.888-2.11-2.361-4.283-2.986-5.206l-.041-.06l-2.098-2.82a2.536 2.536 0 0 1 4.05-3.054l1.088 1.424l-.344-7.953a2.385 2.385 0 0 1 4.399-1.378z");
}

.e5wz7zbbf {
  stop-color: var(--svg-color--634638, #634638);
}

.e88yeyaxk {
  d: path("M25.607 8.517a.673.673 0 0 0-.687.664c-.027 2.142-.092 7.103-.17 9.627c-.014.433.282.794.658.8c.37.007.677-.333.685-.76l.177-9.644a.675.675 0 0 0-.663-.687");
}

.ey86uh85b {
  d: path("M21.37 5.451c-.432 0-.78.35-.777.782c.015 2.195.043 7.039.006 9.523a.776.776 0 0 0 .776.789a.77.77 0 0 0 .772-.772V6.228a.777.777 0 0 0-.777-.777");
}

.fqe7ixbng {
  d: path("M13.562 4.49a2.406 2.406 0 0 1 4.81-.135l.026.945a2.406 2.406 0 0 1 4.393 1.4l-.026 1.37a2.406 2.406 0 0 1 4.16 1.736l-.335 8.822c-.005 1.33-.15 3.695-1.004 5.76c-1.208 3.267-4.34 5.595-8.016 5.595c-3.715 0-6.876-2.379-8.055-5.701c-.888-2.11-2.361-4.283-2.986-5.206l-.041-.06l-2.098-2.82a2.536 2.536 0 0 1 4.05-3.054l1.088 1.424l-.344-7.953a2.385 2.385 0 0 1 4.399-1.378z");
}

.ft5dv1b6b {
  fill: none;
}

.g_aaj6gld {
  stop-color: var(--svg-color--92735f, #92735F);
}

.g62rx8b1e {
  fill: var(--svg-color--c19988, #C19988);
  d: path("m11.68 6.118l.13 9.484l1.284-.188l-.194-9.317a.61.61 0 0 0-1.22.021");
}

.hcnm0gbnl {
  stop-color: var(--svg-color--936565, #936565);
}

.hdbhm0bnq {
  stop-color: var(--svg-color--b3857a, #B3857A);
}

.i04f7joye {
  stop-color: var(--svg-color--8d5e4f, #8D5E4F);
}

.i1zhfgnpn {
  stop-color: var(--svg-color--a87e69, #A87E69);
  stop-opacity: 0;
}

.i94u7374x {
  stop-color: var(--svg-color--d0a88e, #D0A88E);
}

.itzhybc5e {
  stop-color: var(--svg-color--9a7d67, #9A7D67);
}

.j84_0ishg {
  stop-color: var(--svg-color--a47a65, #A47A65);
}

.jgwlmcmzo {
  stop-color: var(--svg-color--cca38e, #CCA38E);
  stop-opacity: 0;
}

.jhesu-hxj {
  stop-color: var(--svg-color--bf9685, #BF9685);
}

.jrl5b5bpz {
  d: path("m18.401 5.295l-.018 12.156h4.187l.197-9.383l-.002.002l.026-1.37a2.406 2.406 0 0 0-4.39-1.405");
}

.jvw4ebt-r {
  stop-color: var(--svg-color--92735f, #92735F);
  stop-opacity: 0;
}

.k-0lcabla {
  stop-color: var(--svg-color--946354, #946354);
}

.k3lbqdbda {
  stop-color: var(--svg-color--81584e, #81584E);
  stop-opacity: 0;
}

.kxe70_b8r {
  stop-color: var(--svg-color--bc9181, #BC9181);
}

.l8nkzzbwc {
  stop-color: var(--svg-color--95755e, #95755E);
  stop-opacity: 0;
}

.la18v8bdt {
  d: path("m4.83 12.708l.08-.06a2.536 2.536 0 0 1 3.53.494l1.084 1.419l.162 4.512z");
}

.mta-gxbha {
  stop-color: var(--svg-color--b48974, #B48974);
  stop-opacity: 0;
}

.n5ewo8byt {
  stop-color: var(--svg-color--a87e69, #A87E69);
}

.n9j7mnb6l {
  stop-color: var(--svg-color--855d50, #855D50);
}

.nvhcxvb-x {
  stop-color: var(--svg-color--916a5e, #916A5E);
}

.o602s3q4k {
  stop-color: var(--svg-color--916a5e, #916A5E);
  stop-opacity: 0;
}

.o7wbjjbaq {
  stop-color: var(--svg-color--9a7d67, #9A7D67);
  stop-opacity: 0;
}

.oa5qxrb6u {
  stop-color: var(--svg-color--d0a88e, #D0A88E);
  stop-opacity: 0;
}

.ojod5htzj {
  stop-color: var(--svg-color--b3857a, #B3857A);
  stop-opacity: 0;
}

.op60lab0l {
  stop-color: var(--svg-color--a2846c, #A2846C);
  stop-opacity: 0;
}

.oq92pq7ha {
  d: path("m9.513 14.547l.12 2.78l4.125-1.72L13.58 5.23a2.384 2.384 0 0 0-4.396 1.383l.344 7.953z");
}

.oxcebbo2u {
  stop-color: var(--svg-color--95755e, #95755E);
}

.p0wx8vbfh {
  stop-color: var(--svg-color--946354, #946354);
  stop-opacity: 0;
}

.p3kpdx-jh {
  d: path("M26.147 20.014c-.17 3.648-1.909 6.402-3.711 7.568l1.882-19.827c2.014 0 2.252 1.511 2.226 2.452c-.053 1.961-.228 6.16-.397 9.807");
}

.pc_ypn7fw {
  d: path("M16.311 5.196c0-.302-.06-.58-.186-.81c-.209-.38-.43-.855-.24-1.244c.153-.311.51-.487.82-.33c1.064.542 1.196 1.67 1.169 2.384v10.593a.773.773 0 0 1-.773.773a.776.776 0 0 1-.776-.788c.049-3.493-.014-9.664-.014-10.578");
}

.ql9m72tpr {
  stop-color: var(--svg-color--634535, #634535);
}

.s-2xfac7e {
  stop-color: var(--svg-color--c89b84, #C89B84);
  stop-opacity: 0;
}

.s1g--acyf {
  stop-color: var(--svg-color--634638, #634638);
  stop-opacity: 0;
}

.sne-vkbdr {
  stop-color: var(--svg-color--bf9685, #BF9685);
  stop-opacity: 0;
}

.sqmhaybyy {
  stop-color: var(--svg-color--81584e, #81584E);
}

.t1pbx2bxi {
  stop-color: var(--svg-color--cca38e, #CCA38E);
}

.t2y--rbpl {
  d: path("m22.775 8.06l-.267 8.548l4.156.343l.26-7.145a2.406 2.406 0 0 0-4.149-1.747");
}

.udexd28np {
  stop-color: var(--svg-color--bc9181, #BC9181);
  stop-opacity: 0;
}

.uj-6nfb_i {
  stop-color: var(--svg-color--94715b, #94715B);
}

.uyel8mbjo {
  stop-color: var(--svg-color--926563, #926563);
  stop-opacity: 0;
}

.va8v2kriz {
  d: path("m18.399 5.298l-.001.002l-.027-.945a2.406 2.406 0 0 0-4.808-.022l.007.455l.013.447l-.005-.008l.172 12.6h4.687z");
}

.wko5rrbnp {
  stop-color: var(--svg-color--634535, #634535);
  stop-opacity: 0;
}

.wph0opaub {
  stop-color: var(--svg-color--c79e8a, #C79E8A);
}

.x9sp0lxpb {
  stop-color: var(--svg-color--b48974, #B48974);
}

.xbduuqv3a {
  stop-color: var(--svg-color--c89b84, #C89B84);
}

.xdyu8nbjh {
  stop-color: var(--svg-color--94715b, #94715B);
  stop-opacity: 0;
}

.yafcvbc6z {
  d: path("M9.58 16.317v3.101l-3.762-4.823a.93.93 0 0 1 1.458-1.152z");
}

.ys91hqkls {
  stop-color: var(--svg-color--936565, #936565);
  stop-opacity: 0;
}

.zp9vxoqbl {
  stop-color: var(--svg-color--a47a65, #A47A65);
  stop-opacity: 0;
}

</style>
