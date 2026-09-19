<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i2hJ2ob)"><path class="k6hl-_bcv"/><path fill="url(#iekeZgd)" class="i49u0jb4h"/><path fill="url(#iUABKzC)" class="i49u0jb4h"/></g><path fill="url(#in4qnfd)" class="d94ttnbbo"/><g filter="url(#iOH6bsJ)"><path fill="url(#iTrh89b)" class="afuvsp37i"/></g><path fill="url(#iJCHHnb)" class="o8rsn9ban"/><path fill="url(#irQjgSd)" class="o8rsn9ban"/><path fill="url(#iWvBfCe)" class="o8rsn9ban"/><path fill="url(#if6OWve)" class="o8rsn9ban"/><path fill="url(#i3Xlwqb)" class="o8rsn9ban"/><g filter="url(#iLNiP7b)"><path class="t0bu66bul"/></g><path fill="url(#iSZEWDd)" class="jlkxt1b-o"/><path fill="url(#ijd7PHc)" class="jlkxt1b-o"/><path fill="url(#ijeIbkc)" class="jlkxt1b-o"/><path fill="url(#ia1IGAb)" class="jlkxt1b-o"/><g filter="url(#i3ZhUle)"><path fill="url(#iDn7Hmx)" class="p8xsk0bxc"/></g><path fill="url(#im5EZAc)" class="vqw4gwb7s"/><path fill="url(#ilyN2Rc)" class="vqw4gwb7s"/><path fill="url(#iIFJ7Ob)" class="vqw4gwb7s"/><path fill="url(#iguKX1b)" class="vqw4gwb7s"/><g filter="url(#i82VKYZ)"><path fill="url(#irTlTNe)" class="vbaxtlbwt"/></g><path fill="url(#iILFmec)" class="i49u0jb4h"/><path fill="url(#i9ANuxy)" class="i49u0jb4h"/><path fill="url(#iXjIFGe)" class="i49u0jb4h"/><path fill="url(#ihAWjNb)" class="i49u0jb4h"/><path fill="url(#igM8qbc)" class="i49u0jb4h"/><path fill="url(#iiYHxMb)" class="i49u0jb4h"/><g filter="url(#i2VZvla)"><path fill="url(#ireS19d)" class="mddybub0i"/></g><path fill="url(#i7ofazz)" class="aggo5pb1z"/><path fill="url(#i3NvaLc)" class="aggo5pb1z"/><path fill="url(#i5jftvd)" class="aggo5pb1z"/><g filter="url(#ir2vaOd)"><path fill="url(#ivtAb4c)" class="n18ry-xel"/></g><defs><linearGradient id="iTrh89b" x1="18.414" x2="11.624" y1="6.372" y2="10.681" gradientUnits="userSpaceOnUse"><stop class="x9sp0lxpb"/><stop offset="1" class="mta-gxbha"/></linearGradient><linearGradient id="iJCHHnb" x1="20.155" x2="20.267" y1="8.999" y2="11.049" gradientUnits="userSpaceOnUse"><stop class="nvhcxvb-x"/><stop offset="1" class="o602s3q4k"/></linearGradient><linearGradient id="irQjgSd" x1="20.939" x2="20.924" y1="14.023" y2="13.039" gradientUnits="userSpaceOnUse"><stop class="n9j7mnb6l"/><stop offset="1" class="ca0jfjbzt"/></linearGradient><linearGradient id="if6OWve" x1="15.221" x2="17.221" y1="11.47" y2="10.851" gradientUnits="userSpaceOnUse"><stop offset=".236" class="hdbhm0bnq"/><stop offset="1" class="ojod5htzj"/></linearGradient><linearGradient id="iSZEWDd" x1="22.111" x2="22.164" y1="12.695" y2="15.774" gradientUnits="userSpaceOnUse"><stop class="sqmhaybyy"/><stop offset="1" class="k3lbqdbda"/></linearGradient><linearGradient id="ijeIbkc" x1="22.485" x2="22.485" y1="18.877" y2="17.669" gradientUnits="userSpaceOnUse"><stop class="j84_0ishg"/><stop offset="1" class="zp9vxoqbl"/></linearGradient><linearGradient id="ia1IGAb" x1="14.924" x2="17.855" y1="15.226" y2="15.431" gradientUnits="userSpaceOnUse"><stop class="hdbhm0bnq"/><stop offset="1" class="ojod5htzj"/></linearGradient><linearGradient id="iDn7Hmx" x1="29.845" x2="23.682" y1="17.53" y2="26.161" gradientUnits="userSpaceOnUse"><stop class="wph0opaub"/><stop offset="1" class="cvo9a4s4m"/></linearGradient><linearGradient id="im5EZAc" x1="21.177" x2="21.229" y1="17.598" y2="20.382" gradientUnits="userSpaceOnUse"><stop class="i04f7joye"/><stop offset="1" class="c7c1ompfs"/></linearGradient><linearGradient id="ilyN2Rc" x1="21.149" x2="21.139" y1="23.511" y2="22.04" gradientUnits="userSpaceOnUse"><stop class="n5ewo8byt"/><stop offset="1" class="i1zhfgnpn"/></linearGradient><linearGradient id="iIFJ7Ob" x1="16.111" x2="18.85" y1="19.414" y2="19.943" gradientUnits="userSpaceOnUse"><stop class="hdbhm0bnq"/><stop offset="1" class="ojod5htzj"/></linearGradient><linearGradient id="irTlTNe" x1="26.549" x2="12.986" y1="21.803" y2="21.803" gradientUnits="userSpaceOnUse"><stop class="t1pbx2bxi"/><stop offset="1" class="jgwlmcmzo"/></linearGradient><linearGradient id="iILFmec" x1="9.401" x2="9.401" y1="27.313" y2="21.959" gradientUnits="userSpaceOnUse"><stop class="bpzk7poxj"/><stop offset="1" class="bcg91z1pi"/></linearGradient><linearGradient id="ireS19d" x1="15.869" x2="15.975" y1="27.154" y2="24.185" gradientUnits="userSpaceOnUse"><stop class="xbduuqv3a"/><stop offset="1" class="s-2xfac7e"/></linearGradient><linearGradient id="i7ofazz" x1="19.391" x2="19.145" y1="21.684" y2="24.011" gradientUnits="userSpaceOnUse"><stop class="k-0lcabla"/><stop offset="1" class="p0wx8vbfh"/></linearGradient><linearGradient id="i3NvaLc" x1="15.049" x2="17.596" y1="24.011" y2="24.113" gradientUnits="userSpaceOnUse"><stop class="kxe70_b8r"/><stop offset="1" class="udexd28np"/></linearGradient><linearGradient id="ivtAb4c" x1="23.477" x2="9.916" y1="25.984" y2="25.735" gradientUnits="userSpaceOnUse"><stop class="i94u7374x"/><stop offset="1" class="oa5qxrb6u"/></linearGradient><radialGradient id="iekeZgd" cx="0" cy="0" r="1" gradientTransform="matrix(2.62497 5.12502 -18.39164 9.41998 4.924 9.445)" gradientUnits="userSpaceOnUse"><stop class="c8rwtvj3l"/><stop offset="1" class="uyel8mbjo"/></radialGradient><radialGradient id="iUABKzC" cx="0" cy="0" r="1" gradientTransform="rotate(169.33 9.689 3.852)scale(2.48176 3.91796)" gradientUnits="userSpaceOnUse"><stop class="oxcebbo2u"/><stop offset="1" class="l8nkzzbwc"/></radialGradient><radialGradient id="in4qnfd" cx="0" cy="0" r="1" gradientTransform="matrix(-.7422 -1.1133 3.24362 -2.1624 16.611 10.083)" gradientUnits="userSpaceOnUse"><stop class="e5wz7zbbf"/><stop offset="1" class="s1g--acyf"/></radialGradient><radialGradient id="iWvBfCe" cx="0" cy="0" r="1" gradientTransform="rotate(-112.681 18.022 -1.981)scale(1.13462 1.78724)" gradientUnits="userSpaceOnUse"><stop class="ql9m72tpr"/><stop offset="1" class="wko5rrbnp"/></radialGradient><radialGradient id="i3Xlwqb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.68398 .97056 -2.27507 -3.94737 28.205 10.008)" gradientUnits="userSpaceOnUse"><stop class="azqf21bvt"/><stop offset="1" class="op60lab0l"/></radialGradient><radialGradient id="ijd7PHc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.62144 .87499 -1.31993 -2.44595 29.983 14.601)" gradientUnits="userSpaceOnUse"><stop class="itzhybc5e"/><stop offset="1" class="o7wbjjbaq"/></radialGradient><radialGradient id="iguKX1b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.354 .79135 -1.24433 -2.12908 27.75 19.322)" gradientUnits="userSpaceOnUse"><stop class="g_aaj6gld"/><stop offset="1" class="jvw4ebt-r"/></radialGradient><radialGradient id="i9ANuxy" cx="0" cy="0" r="1" gradientTransform="matrix(2.2675 -.1875 .14684 1.77572 16 12.664)" gradientUnits="userSpaceOnUse"><stop class="jhesu-hxj"/><stop offset="1" class="sne-vkbdr"/></radialGradient><radialGradient id="iXjIFGe" cx="0" cy="0" r="1" gradientTransform="matrix(2.17374 -.09375 .08645 2.00449 16 17.383)" gradientUnits="userSpaceOnUse"><stop class="jhesu-hxj"/><stop offset="1" class="sne-vkbdr"/></radialGradient><radialGradient id="ihAWjNb" cx="0" cy="0" r="1" gradientTransform="rotate(-1.909 645.796 -462.53)scale(1.87604)" gradientUnits="userSpaceOnUse"><stop class="jhesu-hxj"/><stop offset="1" class="sne-vkbdr"/></radialGradient><radialGradient id="igM8qbc" cx="0" cy="0" r="1" gradientTransform="rotate(-63.435 27.813 -.16)scale(2.37582 3.13027)" gradientUnits="userSpaceOnUse"><stop class="jhesu-hxj"/><stop offset="1" class="sne-vkbdr"/></radialGradient><radialGradient id="iiYHxMb" cx="0" cy="0" r="1" gradientTransform="rotate(62.242 -2.228 12.076)scale(3.03562 12.0503)" gradientUnits="userSpaceOnUse"><stop class="hcnm0gbnl"/><stop offset="1" class="ys91hqkls"/></radialGradient><radialGradient id="i5jftvd" cx="0" cy="0" r="1" gradientTransform="rotate(154.485 10.034 14.562)scale(1.95209 5.21489)" gradientUnits="userSpaceOnUse"><stop class="uj-6nfb_i"/><stop offset="1" class="xdyu8nbjh"/></radialGradient><filter id="i2hJ2ob" width="28.215" height="24.039" x="2.017" y="2.888" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-1"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.603922 0 0 0 0 0.34902 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_6491"/></filter><filter id="iOH6bsJ" width="7.823" height="5.458" x="11.832" y="4.872" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6491" stdDeviation=".375"/></filter><filter id="iLNiP7b" width="12.102" height="3.414" x="15.398" y="10.68" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6491" stdDeviation=".5"/></filter><filter id="i3ZhUle" width="15.808" height="4.064" x="14.438" y="14.813" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6491" stdDeviation=".5"/></filter><filter id="i82VKYZ" width="13.094" height="3.555" x="14.455" y="19.593" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6491" stdDeviation=".5"/></filter><filter id="i2VZvla" width="21.827" height="6.11" x="3.418" y="21.436" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6491" stdDeviation=".5"/></filter><filter id="ir2vaOd" width="13.092" height="3.521" x="11.391" y="23.749" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6491" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:rightwards-hand-medium" /></template>
<style>
.afuvsp37i {
  d: path("M15.683 9.58h-3.1l4.822-3.762a.93.93 0 0 1 1.152 1.458z");
}

.aggo5pb1z {
  d: path("m23.94 22.775l-8.548-.267l-.343 4.156l7.145.26a2.406 2.406 0 0 0 1.747-4.149");
}

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

.d94ttnbbo {
  d: path("m19.292 4.831l.06.079a2.536 2.536 0 0 1-.494 3.53l-1.419 1.084l-4.512.162z");
}

.e5wz7zbbf {
  stop-color: var(--svg-color--634638, #634638);
}

.ft5dv1b6b {
  fill: none;
}

.g_aaj6gld {
  stop-color: var(--svg-color--92735f, #92735F);
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

.i49u0jb4h {
  d: path("M27.51 13.562a2.406 2.406 0 0 1 .135 4.81l-.945.026a2.406 2.406 0 0 1-1.4 4.393l-1.37-.026a2.406 2.406 0 0 1-1.736 4.16l-8.822-.335c-1.33-.005-3.695-.15-5.76-1.004c-3.267-1.207-5.595-4.34-5.595-8.016c0-3.715 2.379-6.876 5.701-8.054c2.11-.889 4.284-2.362 5.206-2.987l.06-.041l2.82-2.098a2.536 2.536 0 0 1 3.054 4.05l-1.424 1.088l7.953-.344a2.385 2.385 0 0 1 1.378 4.4z");
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

.jlkxt1b-o {
  d: path("m26.702 18.4l-.002-.002l.945-.026a2.406 2.406 0 0 0 .022-4.81l-.455.008l-.447.013l.008-.005l-12.6.172v4.687z");
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

.k6hl-_bcv {
  fill: var(--svg-color--b3857a, #B3857A);
  d: path("M27.51 13.562a2.406 2.406 0 0 1 .135 4.81l-.945.026a2.406 2.406 0 0 1-1.4 4.393l-1.37-.026a2.406 2.406 0 0 1-1.736 4.16l-8.822-.335c-1.33-.005-3.695-.15-5.76-1.004c-3.267-1.207-5.595-4.34-5.595-8.016c0-3.715 2.379-6.876 5.701-8.054c2.11-.889 4.284-2.362 5.206-2.987l.06-.041l2.82-2.098a2.536 2.536 0 0 1 3.054 4.05l-1.424 1.088l7.953-.344a2.385 2.385 0 0 1 1.378 4.4z");
}

.kxe70_b8r {
  stop-color: var(--svg-color--bc9181, #BC9181);
}

.l8nkzzbwc {
  stop-color: var(--svg-color--95755e, #95755E);
  stop-opacity: 0;
}

.mddybub0i {
  d: path("M11.986 26.147c-3.648-.17-6.402-1.909-7.568-3.711l19.827 1.882c0 2.014-1.511 2.252-2.452 2.226c-1.961-.053-6.16-.228-9.807-.398");
}

.mta-gxbha {
  stop-color: var(--svg-color--b48974, #B48974);
  stop-opacity: 0;
}

.n18ry-xel {
  d: path("M23.483 25.607a.673.673 0 0 0-.664-.687c-2.142-.027-7.103-.092-9.627-.17c-.433-.014-.794.282-.8.659c-.007.37.333.677.76.684l9.644.177c.373.007.68-.29.687-.663");
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

.o8rsn9ban {
  d: path("m17.453 9.513l-2.78.12l1.72 4.125l10.377-.178a2.384 2.384 0 0 0-1.383-4.396l-7.953.344z");
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

.oxcebbo2u {
  stop-color: var(--svg-color--95755e, #95755E);
}

.p0wx8vbfh {
  stop-color: var(--svg-color--946354, #946354);
  stop-opacity: 0;
}

.p8xsk0bxc {
  d: path("M26.804 16.311c.302 0 .58-.06.81-.186c.38-.209.855-.43 1.244-.24c.311.153.487.51.33.82c-.542 1.065-1.67 1.196-2.384 1.169H16.211a.77.77 0 0 1-.773-.772c0-.434.355-.782.788-.776c3.493.048 9.664-.015 10.578-.015");
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

.t0bu66bul {
  fill: var(--svg-color--c19988, #C19988);
  d: path("m25.882 11.68l-9.484.129l.189 1.285l9.316-.194a.61.61 0 0 0-.021-1.22");
}

.t1pbx2bxi {
  stop-color: var(--svg-color--cca38e, #CCA38E);
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

.vbaxtlbwt {
  d: path("M26.549 21.37c0-.432-.35-.78-.782-.777c-2.195.015-7.039.042-9.523.006a.776.776 0 0 0-.789.776c0 .426.346.772.772.772h9.545a.777.777 0 0 0 .777-.777");
}

.vqw4gwb7s {
  d: path("m26.705 18.401l-12.156-.018v4.187l9.383.197l-.002-.002l1.37.026a2.406 2.406 0 0 0 1.405-4.39");
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

.ys91hqkls {
  stop-color: var(--svg-color--936565, #936565);
  stop-opacity: 0;
}

.zp9vxoqbl {
  stop-color: var(--svg-color--a47a65, #A47A65);
  stop-opacity: 0;
}

</style>
