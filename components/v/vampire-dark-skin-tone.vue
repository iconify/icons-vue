<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<linearGradient id="SVGBbqfvdGB" x1="64" x2="64" y1="63.947" y2="14.811" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset=".003" class="fs5n-8cqc"/><stop offset=".176" class="pyh65pbfk"/><stop offset=".497" class="cf_7htt0g"/><stop offset=".927" class="fcwdfbcyc"/><stop offset="1" class="ddn_vwuyg"/></linearGradient><path fill="url(#SVGBbqfvdGB)" class="xvjp3wb0a"/><linearGradient id="SVGcnfIDUaH" x1="64" x2="64" y1="64.021" y2="18.565" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset=".003" class="r-jm3dbhh"/><stop offset=".235" class="axcnju7ll"/><stop offset=".443" class="h2y05rb7n"/><stop offset=".642" class="r44bgirxu"/><stop offset=".834" class="egtjl9tnn"/><stop offset="1" class="eywy9vyph"/></linearGradient><path fill="url(#SVGcnfIDUaH)" class="kkqjzkblv"/><path class="isnq3fbtv"/><radialGradient id="SVG3mOnqzqQ" cx="99.712" cy="43.369" r="23.622" gradientTransform="matrix(1 0 0 .4912 -21.202 62.292)" gradientUnits="userSpaceOnUse"><stop offset=".728" class="qpo2vg_rh"/><stop offset="1" class="g00j4bcaa"/></radialGradient><path fill="url(#SVG3mOnqzqQ)" class="sqa3opb1x"/><radialGradient id="SVG3LZyGCZF" cx="101.804" cy="43.364" r="23.437" gradientTransform="matrix(-1 0 0 .4912 151.388 62.3)" gradientUnits="userSpaceOnUse"><stop offset=".728" class="qpo2vg_rh"/><stop offset="1" class="g00j4bcaa"/></radialGradient><path fill="url(#SVG3LZyGCZF)" class="bvvux-bna"/><radialGradient id="SVGgfgt5bYk" cx="77.892" cy="51.929" r="6.921" gradientTransform="rotate(154.924 85.366 61.352)scale(1 .7418)" gradientUnits="userSpaceOnUse"><stop offset=".663" class="g00j4bcaa"/><stop offset="1" class="qpo2vg_rh"/></radialGradient><path fill="url(#SVGgfgt5bYk)" class="o-anpxbku"/><radialGradient id="SVGPKPS0cNc" cx="92.243" cy="63.288" r="25.988" gradientTransform="matrix(-.0746 -.9972 .8311 -.0622 42.336 160.527)" gradientUnits="userSpaceOnUse"><stop offset=".725" class="qpo2vg_rh"/><stop offset="1" class="g00j4bcaa"/></radialGradient><path fill="url(#SVGPKPS0cNc)" class="zpb-racsd"/><radialGradient id="SVG6cHJbcfs" cx="43.626" cy="61.654" r="26.634" gradientTransform="matrix(.0746 -.9972 -.8311 -.0622 89.687 115.972)" gradientUnits="userSpaceOnUse"><stop offset=".725" class="qpo2vg_rh"/><stop offset="1" class="g00j4bcaa"/></radialGradient><path fill="url(#SVG6cHJbcfs)" class="uupsjqzwg"/><radialGradient id="SVGIzLaGenZ" cx="26.076" cy="50.007" r="6.638" gradientTransform="rotate(205.076 4.896 52.533)scale(-1 .7418)" gradientUnits="userSpaceOnUse"><stop offset=".663" class="g00j4bcaa"/><stop offset="1" class="qpo2vg_rh"/></radialGradient><path fill="url(#SVGIzLaGenZ)" class="jo5h2qs8y"/><radialGradient id="SVGKskNrcvz" cx="65.112" cy="6.25" r="60.448" gradientTransform="matrix(1 0 0 -.5085 0 126.928)" gradientUnits="userSpaceOnUse"><stop offset=".568" class="wk_lp_wlk"/><stop offset="1" class="aplh-7tkj"/></radialGradient><path fill="url(#SVGKskNrcvz)" class="n6wkpbbju"/><linearGradient id="SVGJR0lddGf" x1="63.96" x2="63.96" y1="33.575" y2="8.069" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset=".782" class="vc--wpv5i"/><stop offset="1" class="tlfnspbae"/></linearGradient><path fill="url(#SVGJR0lddGf)" class="d-u7p1bfj"/><path class="zilj3pbfp"/><path class="r09gvzfwd"/><circle class="bt1v6pbgu"/><circle class="peky8886y"/><path class="trmvxsb5t"/><path class="sj6ll9bld"/><path class="f4vbxhbgs"/><path class="k42o46bem"/><defs><path id="SVGGjGXGeia" class="nr0f06_eh"/></defs><clipPath id="SVG97fMdjCB"><use href="#SVGGjGXGeia"/></clipPath><g clip-path="url(#SVG97fMdjCB)" class="n1mjunbsu"><path class="mlhvz8g3m"/></g><path class="th0es8bgm"/><g class="d2ol71wkq"><ellipse class="xm_cxnkcf"/><ellipse class="qi4mcqr9e"/></g><path class="s-bsi3lap"/><radialGradient id="SVGeXN2bqcO" cx="81.76" cy="85.078" r="35.633" gradientTransform="matrix(.3076 .9515 .706 -.2282 -3.197 -15.328)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="qpo2vg_rh"/><stop offset="1" class="g00j4bcaa"/></radialGradient><path fill="url(#SVGeXN2bqcO)" class="z0wnxiz1y"/><radialGradient id="SVGiim2xdfd" cx="46.926" cy="125.144" r="9.343" gradientTransform="matrix(.8813 .4726 .5603 -1.045 -64.194 112.8)" gradientUnits="userSpaceOnUse"><stop offset=".58" class="g00j4bcaa"/><stop offset="1" class="qpo2vg_rh"/></radialGradient><path fill="url(#SVGiim2xdfd)" class="b36gj8bmp"/><radialGradient id="SVG7CMZ2dgn" cx="161.339" cy="62.928" r="28.721" gradientTransform="matrix(-.9378 -.3944 -.2182 .5285 233.195 51.544)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="qpo2vg_rh"/><stop offset="1" class="g00j4bcaa"/></radialGradient><path fill="url(#SVG7CMZ2dgn)" class="m1-eewucy"/><radialGradient id="SVGyjkSbb2f" cx="43.489" cy="117.093" r="8.56" gradientTransform="matrix(1 0 0 -1.2233 0 155.965)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="qpo2vg_rh"/><stop offset="1" class="g00j4bcaa"/></radialGradient><path fill="url(#SVGyjkSbb2f)" class="r_-sp5lyw"/><radialGradient id="SVGGgYpicmV" cx="44.575" cy="100.385" r="16.083" gradientTransform="matrix(-.9657 -.2598 -.2432 .9037 109.807 -51.275)" gradientUnits="userSpaceOnUse"><stop offset=".66" class="qpo2vg_rh"/><stop offset="1" class="g00j4bcaa"/></radialGradient><path fill="url(#SVGGgYpicmV)" class="gtqbt9beb"/><radialGradient id="SVGtv4lEC5i" cx="38.375" cy="86.217" r="16.86" gradientTransform="rotate(187.833 -2.598 79.64)scale(-1 1.4052)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="qpo2vg_rh"/><stop offset="1" class="g00j4bcaa"/></radialGradient><path fill="url(#SVGtv4lEC5i)" class="jrj9rl_ef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:vampire-dark-skin-tone" /></template>
<style>
.aplh-7tkj {
  stop-color: var(--svg-color--616161, #616161);
}

.axcnju7ll {
  stop-color: var(--svg-color--f30000, #f30000);
}

.b36gj8bmp {
  d: path("M56.95 7.39c-1.1.53-2.06 1.06-2.9 1.51c-.96.52-7.17 3.97-11.51 1.5c-2.67-1.52-2.67-5.58-2.67-5.72c-1.23 1.57-4.95 12.78 5.93 13.53c4.69.32 7.58-3.77 9.3-7.23c.62-1.26 1.59-3.1 1.85-3.59");
}

.bt1v6pbgu {
  cx: 42.75px;
  cy: 104.52px;
  r: 3.69px;
  fill: var(--svg-color--f19102, #f19102);
}

.bvvux-bna {
  d: path("M64.01 95.79v-9.44l-28.57-2.26s-2.73 1.4-2.05 3.7c2.84 2.69 5.49 8.11 21.68 8.21z");
}

.cf_7htt0g {
  stop-color: var(--svg-color--494747, #494747);
}

.d-u7p1bfj {
  d: path("M51.33 123.96h25l.53-26.79l-3.78-1.14l.15-5.92H54.76l.18 5.92l-3.88 1.14z");
}

.d2ol71wkq {
  fill: var(--svg-color--1a1717, #1a1717);
}

.ddn_vwuyg {
  stop-color: var(--svg-color--070606, #070606);
}

.egtjl9tnn {
  stop-color: var(--svg-color--bd0000, #bd0000);
}

.eywy9vyph {
  stop-color: var(--svg-color--a00000, #a00000);
}

.f4vbxhbgs {
  fill: var(--svg-color--33251f, #33251f);
  d: path("M67.86 68.06c-.11-.04-.21-.07-.32-.08h-7.08c-.11.01-.22.04-.32.08c-.64.26-.99.92-.69 1.63s1.71 2.69 4.55 2.69s4.25-1.99 4.55-2.69c.3-.71-.05-1.37-.69-1.63");
}

.fcwdfbcyc {
  stop-color: var(--svg-color--111010, #111010);
}

.fs5n-8cqc {
  stop-color: var(--svg-color--787676, #787676);
}

.g00j4bcaa {
  stop-color: var(--svg-color--444140, #444140);
}

.gtqbt9beb {
  d: path("m39.07 17.73l-4.81-.77c-.19 0-.83.06-1.18.11c-2.71.38-5.9 1.78-7.63 5.36c-1.86 3.86-1.81 7.17-1.3 9.38c.15.74.45 1.58.45 1.58s2.38-2.26 8.05-2.41z");
}

.h2y05rb7n {
  stop-color: var(--svg-color--e90000, #e90000);
}

.isnq3fbtv {
  fill: var(--svg-color--232020, #232020);
  d: path("M99.03 80c-1.04-2.01-.2-4.02 3.07-7.39c4.05-4.18 9.28-14.99 3.97-25.94l-1.95-1.84s-17.81.08-22.03.08H46.11c-4.22 0-22.03-.08-22.03-.08l-2.69 1.83c.02.06.04.11.07.17c-4.35 10.69.33 21.22 4.64 25.76c2.71 2.86 4.17 5.1 3.06 7.44c-.56 1.17-1.43 1.86-2.67 2.1l-2.14.43l1.17 1.85c.42.67 1 1.23 1.66 1.63c1.86 1.11 4.13 1.39 5.7 1.43c.18 0 .44.2.83.64c5.07 5.62 9.06 7.42 21.4 7.88l17.82.01c12.46-.44 16.47-2.23 21.56-7.88c.39-.44.65-.63.83-.64c1.57-.04 3.84-.32 5.7-1.43c.67-.4 1.24-.96 1.67-1.63l1.17-1.85l-2.14-.43c-1.19-.23-2.07-.93-2.69-2.14");
}

.jo5h2qs8y {
  d: path("M32.94 83.36c4.28-6.5-4.27-7.56-4.27-7.56s1.5 2.19.48 4.25c-1.12 2.25-4.81 2.53-4.81 2.53s4.9 4.35 8.6.78");
}

.jrj9rl_ef {
  d: path("M24.37 33.58c-2.37 2.1-5.43 6.85-3.18 12.71c1.69 4.41 8.07 6.19 8.07 6.19c0 .02 1.26.4 1.91.4l1.48-21.9c-3 0-6.38.89-8.28 2.6");
}

.k42o46bem {
  fill: var(--svg-color--1a1717, #1a1717);
  d: path("M72.42 76.14c-3.18 1.89-13.63 1.89-16.81 0c-1.83-1.09-3.7.58-2.94 2.24c.75 1.63 6.44 5.42 11.37 5.42s10.55-3.79 11.3-5.42c.75-1.66-1.09-3.33-2.92-2.24");
}

.kkqjzkblv {
  d: path("M4 74.82s52.66-19.89 120 0c0 0-23.56 37.01-60.17 37.01S7.91 82.63 4 74.82");
}

.m1-eewucy {
  d: path("M79.16 5.47c7.32 1.98 10.89 5.71 12.08 10.68c.35 1.46.77 15.08-25.23-.4c-9.67-5.76-7.03-9.36-5.9-9.77c4.42-1.6 10.85-2.73 19.05-.51");
}

.mlhvz8g3m {
  d: path("m55.33 75.66l1 4.99l2.34-3.94zm17.35 0l-1.01 4.99l-2.35-3.94z");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.n6wkpbbju {
  d: path("M64.14 96H64c-25.65.03-52 7.1-52 24.99v2.97h104v-2.97C116 104.13 89.9 96 64.14 96");
}

.nr0f06_eh {
  d: path("M72.42 76.14c-3.18 1.89-13.63 1.89-16.81 0c-1.83-1.09-3.7.58-2.94 2.24c.75 1.63 6.44 5.42 11.37 5.42s10.55-3.79 11.3-5.42c.75-1.66-1.09-3.33-2.92-2.24");
}

.o-anpxbku {
  d: path("M95.26 83.36c-4.28-6.5 5.21-8.93 5.21-8.93l.01.01c-2 2.64-2.3 4.04-1.45 5.57c1.07 1.94 2.4 2.1 3.59 2.32c.73.14 1.25.25 1.25.25s-4.91 4.35-8.61.78");
}

.peky8886y {
  cx: 85.25px;
  cy: 104.52px;
  r: 3.69px;
  fill: var(--svg-color--f19102, #f19102);
}

.pyh65pbfk {
  stop-color: var(--svg-color--6b6969, #6b6969);
}

.qi4mcqr9e {
  cx: 80.44px;
  cy: 58.81px;
  rx: 4.93px;
  ry: 5.1px;
}

.qpo2vg_rh {
  stop-color: var(--svg-color--444140, #444140);
  stop-opacity: 0;
}

.r_-sp5lyw {
  d: path("M39.84 4.68c-.01.01-.03.01-.06.03h-.01c-2.13 1.09-7.34 4.59-5.51 12.25l7.78 1.25c-6.89-6.98-2.17-13.55-2.17-13.55s-.02.01-.03.02");
}

.r-jm3dbhh {
  stop-color: var(--svg-color--f70000, #f70000);
}

.r09gvzfwd {
  fill: none;
  stroke: var(--svg-color--ffcb13, #ffcb13);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M42.73 103.52S49 118.87 64 118.87c15.33 0 21.25-15.35 21.25-15.35");
}

.r44bgirxu {
  stop-color: var(--svg-color--d60000, #d60000);
}

.s-bsi3lap {
  fill: var(--svg-color--232020, #232020);
  d: path("M107.04 41.59c-.01.11-.02.23-.04.35q-.075.585-.18 1.17c-.15.72-.31 1.44-.5 2.15c-.16.58-.33 1.12-.52 1.64c-1.8 4.89-4.86 6.85-5.5 8.23c-.02.13-.04.25-.05.36c-.62 6-4.12 11.92-4.12 12.4c0-6.12-1.14-14.46-2.31-19.85c-2.84-13.08-7.7-16.85-14.73-17.88c-6.35-.93-15.29 8.08-15.29 8.08h-.01s-8.94-9.01-15.3-8.08c-7.03 1.03-12.47 4.69-14.73 17.88c-1.55 9.06-1.74 20.41-1.74 20.41s-3.39-5.21-2.77-15.94c-.02 0-.03-.01-.03-.01s-3.1-.94-5.57-3.01c-.1-.08-.2-.17-.3-.26c-.79-.71-1.49-1.54-1.98-2.5l-.06-.12c-.01-.01-.01-.02-.02-.04c-.07-.19-.15-.38-.21-.57c-2.02-5.94.97-10.44 3.49-12.59c.01-.01.01-.01.02-.01c-.7-1.96-1.56-6.06.86-10.95c2.04-4.12 5.88-5.35 8.81-5.47v-.02c-.14-.56-.23-1.09-.29-1.6c-.11-.89-.12-1.72-.04-2.49c.03-.34.08-.67.15-1.01c.03-.18.07-.35.11-.52c.13-.53.31-1.02.52-1.49c.03-.08.07-.17.11-.25c.08-.16.16-.32.25-.47c1.34-2.44 3.51-3.81 4.7-4.43h.01c.02-.01.04-.02.06-.02c0 0 .01-.01.02-.01c0 .01 0 .01-.01.02l.02-.01l.34 2.43c.01.08.36 2.14 2.33 3.31c2.01 1.2 5.18 1.09 9.15-.31c.56-.21 1.4-.66 2.36-1.18C58.67 6.4 67.28 1.7 80.52 5.89c4.89 1.55 9.94 5.55 10.73 10.27c4.9.33 10.37 5.28 12.81 8.97c.32.49.68 1.17 1.03 2.02c.17.42.36.89.53 1.39c.09.25.18.51.26.78c.03.09.06.18.08.27c.94 3.15 1.59 7.41 1.08 12");
}

.sj6ll9bld {
  fill: var(--svg-color--70534a, #70534a);
  d: path("M64 11.07c-17.4 0-33.52 18.61-33.52 45.4c0 26.64 16.61 39.81 33.52 39.81S97.52 83.1 97.52 56.46c0-26.78-16.12-45.39-33.52-45.39");
}

.sqa3opb1x {
  d: path("M63.99 95.79v-9.44l28.57-2.26s2.93 1.39 2.26 3.69c-2.21 1.74-5.88 9.37-21.89 8.22z");
}

.th0es8bgm {
  fill: var(--svg-color--1a1717, #1a1717);
  d: path("M54.8 49.82c-.93-1.23-3.07-3.01-7.23-3.01s-6.31 1.79-7.23 3.01c-.41.54-.31 1.17-.02 1.55c.26.35 1.04.68 1.9.39s2.54-1.16 5.35-1.18c2.81.02 4.49.89 5.35 1.18s1.64-.03 1.9-.39c.28-.38.39-1.01-.02-1.55m32.87 0c-.93-1.23-3.07-3.01-7.23-3.01s-6.31 1.79-7.23 3.01c-.41.54-.31 1.17-.02 1.55c.26.35 1.04.68 1.9.39s2.54-1.16 5.35-1.18c2.81.02 4.49.89 5.35 1.18s1.64-.03 1.9-.39c.28-.38.39-1.01-.02-1.55");
}

.tlfnspbae {
  stop-color: var(--svg-color--e1e1e1, #e1e1e1);
}

.trmvxsb5t {
  fill: var(--svg-color--3c2b24, #3c2b24);
  d: path("M91.33 50.43H36.67c-5.89 0-10.71 5.14-10.71 11.41s4.82 11.41 10.71 11.41h54.65c5.89 0 10.71-5.14 10.71-11.41s-4.81-11.41-10.7-11.41");
}

.uupsjqzwg {
  d: path("M21.4 46.65c-4.24 10.35.17 21.43 4.69 25.95c3.27 3.27 12.83-8.83 15.68-16.65c.58-1.58 1.1-3.2 1.17-4.88c.05-1.26-.14-2.76-.87-3.83c-.89-1.31-1.93-.96-3.44-.96c-2.88 0-15.49-.74-16.47-.74c.01.01-.76 1.11-.76 1.11");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.wk_lp_wlk {
  stop-color: var(--svg-color--212121, #212121);
}

.xm_cxnkcf {
  cx: 47.56px;
  cy: 58.81px;
  rx: 4.93px;
  ry: 5.1px;
}

.xvjp3wb0a {
  d: path("M4 74.82s23.95-9.01 60-8.84c17.58.08 37.33 3.02 60 8.84c0 0-23.39 45.35-60 45.35S7.91 83.79 4 74.82");
}

.z0wnxiz1y {
  d: path("M100.22 55.5c.16-1.55 4.34-3.6 6.14-10.26c.19-.71.35-1.43.5-2.15c1.46-8.09-1.16-15.52-2.79-17.98c-2.26-3.41-7.1-7.89-11.69-8.81c-.4-.05-.79-.1-1.16-.12c0 0 .33 2.15-.54 3.86c-1.12 2.22-3.41 2.75-3.41 2.75c11.97 11.98 11.12 22 12.95 32.71");
}

.zilj3pbfp {
  fill: none;
  stroke: var(--svg-color--ffcb13, #ffcb13);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M42.73 103.52S49 110.37 64 110.37c15.33 0 21.24-6.85 21.24-6.85");
}

.zpb-racsd {
  d: path("M106.62 46.65c4.25 10.35.11 21.17-4.36 25.8c-.59.61-13.15-8.67-16-16.5c-.57-1.58-1.1-3.2-1.17-4.88c-.05-1.26.14-2.76.87-3.83c.89-1.31 20.16-1.7 20.16-1.7c-.01.01.5 1.11.5 1.11");
}

</style>
