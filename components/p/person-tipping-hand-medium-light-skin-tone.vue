<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="c7mvkcb3f"/><radialGradient id="SVGXSMYkelB" cx="115.385" cy="45.85" r="23.419" gradientTransform="matrix(1 0 0 .4912 -52.548 59.629)" gradientUnits="userSpaceOnUse"><stop offset=".728" class="l1arbqe-k"/><stop offset="1" class="atqdr-9uk"/></radialGradient><path fill="url(#SVGXSMYkelB)" class="oc7xqybnh"/><radialGradient id="SVGokkWe9ms" cx="92.319" cy="49.332" r="6.921" gradientTransform="rotate(154.924 84.432 56.917)scale(1 .7418)" gradientUnits="userSpaceOnUse"><stop offset=".663" class="atqdr-9uk"/><stop offset="1" class="l1arbqe-k"/></radialGradient><path fill="url(#SVGokkWe9ms)" class="c-8c1k3fq"/><radialGradient id="SVGyo5QpdaP" cx="110.255" cy="68.91" r="30.399" gradientTransform="matrix(-.0746 -.9972 .8311 -.0622 18.922 173.324)" gradientUnits="userSpaceOnUse"><stop offset=".725" class="l1arbqe-k"/><stop offset="1" class="atqdr-9uk"/></radialGradient><path fill="url(#SVGyo5QpdaP)" class="qibdvwtxo"/><radialGradient id="SVGm1NRCdkn" cx="28.564" cy="68.91" r="30.399" gradientTransform="matrix(.0746 -.9972 -.8311 -.0622 83.703 91.86)" gradientUnits="userSpaceOnUse"><stop offset=".725" class="l1arbqe-k"/><stop offset="1" class="atqdr-9uk"/></radialGradient><path fill="url(#SVGm1NRCdkn)" class="vygbsf0hk"/><radialGradient id="SVGpaqAgu7N" cx="33.693" cy="45.85" r="23.419" gradientTransform="matrix(-1 0 0 .4912 67.385 59.629)" gradientUnits="userSpaceOnUse"><stop offset=".728" class="l1arbqe-k"/><stop offset="1" class="atqdr-9uk"/></radialGradient><path fill="url(#SVGpaqAgu7N)" class="t8pq51b6m"/><radialGradient id="SVGVnovilvZ" cx="10.627" cy="49.332" r="6.921" gradientTransform="rotate(205.076 4.678 55.267)scale(-1 .7418)" gradientUnits="userSpaceOnUse"><stop offset=".663" class="atqdr-9uk"/><stop offset="1" class="l1arbqe-k"/></radialGradient><path fill="url(#SVGVnovilvZ)" class="j0sdy2bke"/><linearGradient id="SVGZzWJdvkF" x1="50.127" x2="50.127" y1="32" y2="4" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="mujsf_8ht"/><stop offset=".48" class="mcjkwibfm"/><stop offset="1" class="b5pelhk-b"/></linearGradient><path fill="url(#SVGZzWJdvkF)" class="eo6y5xb-n"/><path class="ckaqo9bez"/><path class="dmhq8abza"/><g class="qp89kubki"><ellipse class="n62bmib6i"/><ellipse class="h5wtu34ok"/></g><path class="h1itrv8_j"/><path class="be_qa_pyt"/><path class="ppje29bls"/><g class="vd8kx8r3f"><linearGradient id="SVG11coRz5g" x1="79.315" x2="71.608" y1="14.534" y2="16.177" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset=".265" class="sozvcjboj"/><stop offset="1" class="b8btyqb8s"/></linearGradient><path fill="url(#SVG11coRz5g)" class="a75fqzb5k"/></g><linearGradient id="SVGhrtQ0bho" x1="108.165" x2="100.165" y1="64.135" y2="52.885" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="gg42svbns"/><stop offset="1" class="ms-lo7bhi"/></linearGradient><path fill="url(#SVGhrtQ0bho)" class="s8d41igzf"/><linearGradient id="SVGOsQDfdsK" x1="90.047" x2="90.047" y1="55.897" y2="10.657" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="mujsf_8ht"/><stop offset=".48" class="mcjkwibfm"/><stop offset="1" class="b5pelhk-b"/></linearGradient><path fill="url(#SVGOsQDfdsK)" class="yl8ecwbsj"/><path class="g7ilrsb0d"/><radialGradient id="SVGsQ8Nlxik" cx="66.272" cy="84.946" r="35.633" gradientTransform="matrix(.3076 .9515 .706 -.2282 -14.086 -.622)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="l1arbqe-k"/><stop offset="1" class="atqdr-9uk"/></radialGradient><path fill="url(#SVGsQ8Nlxik)" class="txhrjkn6w"/><radialGradient id="SVGOxdxGeYf" cx="31.534" cy="123.8" r="9.343" gradientTransform="matrix(.8813 .4726 .5603 -1.045 -65.621 118.67)" gradientUnits="userSpaceOnUse"><stop offset=".58" class="atqdr-9uk"/><stop offset="1" class="l1arbqe-k"/></radialGradient><path fill="url(#SVGOxdxGeYf)" class="ndkm28dvi"/><radialGradient id="SVGk4Es4c9a" cx="166.173" cy="48.759" r="28.721" gradientTransform="matrix(-.9378 -.3944 -.2182 .5285 218.89 60.938)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="l1arbqe-k"/><stop offset="1" class="atqdr-9uk"/></radialGradient><path fill="url(#SVGk4Es4c9a)" class="ze8v-0bag"/><radialGradient id="SVGMNMdPcfb" cx="27.782" cy="115.276" r="8.575" gradientTransform="matrix(1 0 0 -1.2233 0 153.742)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="l1arbqe-k"/><stop offset="1" class="atqdr-9uk"/></radialGradient><path fill="url(#SVGMNMdPcfb)" class="r7v0rx1jt"/><radialGradient id="SVG343GncNi" cx="26.603" cy="100.139" r="16.083" gradientTransform="matrix(-.9657 -.2598 -.2432 .9037 76.646 -55.723)" gradientUnits="userSpaceOnUse"><stop offset=".66" class="l1arbqe-k"/><stop offset="1" class="atqdr-9uk"/></radialGradient><path fill="url(#SVG343GncNi)" class="rliier3fk"/><radialGradient id="SVGhkppwdlt" cx="22.787" cy="84.609" r="16.886" gradientTransform="rotate(187.833 -2.584 79.582)scale(-1 1.4052)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="l1arbqe-k"/><stop offset="1" class="atqdr-9uk"/></radialGradient><path fill="url(#SVGhkppwdlt)" class="ip-l7m06s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:person-tipping-hand-medium-light-skin-tone" /></template>
<style>
.a75fqzb5k {
  d: path("M81.54 102.67c-1.62-1.42-7.23-3.04-7.23-3.04L68.83 124h9.5z");
}

.atqdr-9uk {
  stop-color: var(--svg-color--bfa055, #bfa055);
}

.b5pelhk-b {
  stop-color: var(--svg-color--ef6c00, #ef6c00);
}

.b8btyqb8s {
  stop-color: var(--svg-color--262626, #262626);
  stop-opacity: 0;
}

.be_qa_pyt {
  fill: var(--svg-color--6d4c41, #6d4c41);
  d: path("M56.67 76.14c-3.19 1.89-13.63 1.89-16.81 0c-1.83-1.09-3.7.58-2.94 2.24c.75 1.63 6.44 5.42 11.37 5.42s10.55-3.79 11.3-5.42c.76-1.66-1.09-3.33-2.92-2.24");
}

.c-8c1k3fq {
  d: path("M79.35 83.16c-4.28-6.5 5.21-8.93 5.21-8.93l.01.01c-1.65 2.05-2.4 3.84-1.43 5.61c1.21 2.21 4.81 2.53 4.81 2.53s-4.9 4.36-8.6.78");
}

.c7mvkcb3f {
  fill: var(--svg-color--ab872f, #ab872f);
  d: path("M83.15 79.85c-1.25-2.27.34-4.58 3.06-7.44c4.31-4.54 9-15.07 4.64-25.76c.03-.06-.86-1.86-.83-1.92l-1.79-.09c-.57-.08-20.26-.12-39.97-.12s-39.4.04-39.97.12c0 0-2.65 1.95-2.63 2.01c-4.36 10.69.33 21.21 4.64 25.75c2.71 2.86 4.3 5.17 3.06 7.44c-1.21 2.21-4.81 2.53-4.81 2.53s.83 2.26 2.83 3.48c1.85 1.13 4.13 1.39 5.7 1.43c0 0 6.15 8.51 22.23 8.51h17.9c16.08 0 22.23-8.51 22.23-8.51c1.57-.04 3.85-.3 5.7-1.43c2-1.22 2.83-3.48 2.83-3.48s-3.61-.31-4.82-2.52");
}

.ckaqo9bez {
  fill: var(--svg-color--c48e6a, #c48e6a);
  d: path("M38.93 88.95v9.98c0 4.51 3.7 8.17 8.26 8.17h1.65c4.56 0 8.26-3.66 8.26-8.17v-9.98zm36.65-38.52H20.93c-5.89 0-10.71 5.14-10.71 11.41s4.82 11.41 10.71 11.41h54.65c5.89 0 10.71-5.14 10.71-11.41s-4.82-11.41-10.71-11.41");
}

.dmhq8abza {
  fill: var(--svg-color--e0bb95, #e0bb95);
  d: path("M48.25 11.07c-17.4 0-33.52 18.61-33.52 45.4c0 26.64 16.61 39.81 33.52 39.81S81.77 83.1 81.77 56.46c0-26.78-16.11-45.39-33.52-45.39");
}

.eo6y5xb-n {
  d: path("M96.25 124v-2.88c0-16.68-23.56-25.15-47.63-25.12c-18.3.02-36.88 4.38-44.62 14.32V124z");
}

.g7ilrsb0d {
  fill: var(--svg-color--ab872f, #ab872f);
  d: path("M88.33 25.11c-2.44-3.69-7.91-8.64-12.82-8.97c-.79-4.72-5.84-8.72-10.73-10.27c-13.23-4.19-21.84.51-26.47 3.03c-.96.52-7.17 3.97-11.51 1.5c-2.72-1.55-2.67-5.74-2.67-5.74s-8.52 3.25-5.61 12.3c-2.93.12-6.77 1.36-8.8 5.47c-2.42 4.9-1.56 8.99-.86 10.95c-2.52 2.14-5.69 6.69-3.52 12.6c1.64 4.45 8.17 6.5 8.17 6.5c-.46 8.01 1.03 12.94 1.82 14.93c.14.35.63.32.72-.04c.99-3.97 4.36-17.8 4.03-20.21c0 0 11.34-2.25 22.17-10.22c2.2-1.62 4.59-3 7.13-4.01c13.59-5.41 16.43 3.82 16.43 3.82s9.42-1.81 12.26 11.27c1.07 4.9 1.79 12.75 2.4 18.24c.04.39.57.47.72.11c.95-2.18 2.85-6.5 3.3-10.91c.16-1.55 4.34-3.6 6.14-10.26c2.42-8.88-.54-17.42-2.3-20.09");
}

.gg42svbns {
  stop-color: var(--svg-color--e0bb95, #e0bb95);
}

.h1itrv8_j {
  fill: var(--svg-color--ab872f, #ab872f);
  d: path("M39.24 49.82c-.93-1.23-3.07-3.01-7.23-3.01s-6.31 1.79-7.23 3.01c-.41.54-.31 1.17-.02 1.55c.26.35 1.04.68 1.9.39s2.54-1.16 5.35-1.18c2.81.02 4.49.89 5.35 1.18s1.64-.03 1.9-.39c.28-.38.39-1.01-.02-1.55m32.49 0c-.93-1.23-3.07-3.01-7.23-3.01s-6.31 1.79-7.23 3.01c-.41.54-.31 1.17-.02 1.55c.26.35 1.04.68 1.9.39s2.54-1.16 5.35-1.18c2.81.02 4.49.89 5.35 1.18s1.64-.03 1.9-.39c.29-.38.39-1.01-.02-1.55");
}

.h5wtu34ok {
  cx: 64.69px;
  cy: 58.81px;
  rx: 4.93px;
  ry: 5.1px;
}

.ip-l7m06s {
  d: path("M8.63 33.58c-2.37 2.1-5.56 6.79-3.21 12.61c1.78 4.39 8.09 6.29 8.09 6.29c0 .02 1.26.4 1.91.4l1.48-21.9c-3.03 0-5.94.91-7.82 2.22c.02.03-.47.35-.45.38");
}

.j0sdy2bke {
  d: path("M17.18 83.16c4.28-6.5-5.21-8.93-5.21-8.93l-.01.01c1.65 2.05 2.4 3.84 1.43 5.61c-1.21 2.21-4.81 2.53-4.81 2.53s4.9 4.36 8.6.78");
}

.l1arbqe-k {
  stop-color: var(--svg-color--bfa055, #bfa055);
  stop-opacity: 0;
}

.mcjkwibfm {
  stop-color: var(--svg-color--f37f12, #f37f12);
}

.ms-lo7bhi {
  stop-color: var(--svg-color--cca47a, #cca47a);
}

.mujsf_8ht {
  stop-color: var(--svg-color--f78c1f, #f78c1f);
}

.n62bmib6i {
  cx: 31.82px;
  cy: 58.81px;
  rx: 4.93px;
  ry: 5.1px;
}

.ndkm28dvi {
  d: path("M41.21 7.39c-1.1.53-2.06 1.06-2.9 1.51c-.96.52-7.17 3.97-11.51 1.5c-2.67-1.52-2.67-5.58-2.67-5.72c-1.23 1.57-4.95 12.78 5.93 13.53c4.69.32 7.58-3.77 9.3-7.23c.61-1.26 1.58-3.1 1.85-3.59");
}

.oc7xqybnh {
  d: path("M48.24 95.79v-9.44l28.57-2.26l2.6 3.2s-6.15 8.51-22.23 8.51z");
}

.ppje29bls {
  fill: var(--svg-color--c48e6a, #c48e6a);
  d: path("M52.11 68.06c-.11-.04-.21-.07-.32-.08h-7.08c-.11.01-.22.04-.32.08c-.64.26-.99.92-.69 1.63s1.71 2.69 4.55 2.69s4.25-1.99 4.55-2.69c.31-.71-.05-1.37-.69-1.63");
}

.qibdvwtxo {
  d: path("M90.87 46.65c4.25 10.35-.22 21.01-4.41 25.51c-.57.62-3.01 3.01-3.57 4.92c0 0-9.54-13.31-12.39-21.13c-.57-1.58-1.1-3.2-1.17-4.88c-.05-1.26.14-2.76.87-3.83c.89-1.31 20.16-1.7 20.16-1.7c0 .01.51 1.11.51 1.11");
}

.qp89kubki {
  fill: var(--svg-color--5d4037, #5d4037);
}

.r7v0rx1jt {
  d: path("M24.1 4.68c-.01.01-.03.01-.06.03c-.93.39-8.24 3.78-5.51 12.25l7.78 1.25c-6.89-6.98-2.17-13.55-2.17-13.55s-.03.01-.04.02");
}

.rliier3fk {
  d: path("m23.33 17.73l-4.81-.77c-.19 0-.83.06-1.18.11c-2.71.38-5.9 1.78-7.63 5.36c-1.86 3.86-1.81 7.17-1.3 9.38c.15.74.45 1.58.45 1.58s2.38-2.26 8.05-2.41z");
}

.s8d41igzf {
  d: path("M91.32 74.16c2.6.2 6.29.95 8.14.64c1.64-.27 2-1.82 3.71-2.21c3.62-.82 18.26-4.12 19.78-4.49c2.14-.53 2.89-4.53-1.67-5.28c-4.52-.75-13.88 1.18-13.88 1.18s.5-1.43.15-2.38c-.88-2.29-3.87-1.52-5.65-1.1l-10.56 2.99c-5.44 1.87-5.18 10.39-.02 10.65");
}

.sozvcjboj {
  stop-color: var(--svg-color--262626, #262626);
}

.t8pq51b6m {
  d: path("M48.29 95.79v-9.44l-28.57-2.26l-2.6 3.2s6.15 8.51 22.23 8.51z");
}

.txhrjkn6w {
  d: path("M84.47 55.5c.16-1.55 4.34-3.6 6.14-10.26c.19-.71.35-1.43.5-2.15c1.46-8.09-1.16-15.52-2.79-17.98c-2.26-3.41-7.1-7.89-11.69-8.81c-.4-.05-.79-.1-1.16-.12c0 0 .33 2.15-.54 3.86c-1.12 2.22-3.41 2.75-3.41 2.75c11.98 11.98 11.12 22 12.95 32.71");
}

.vd8kx8r3f {
  opacity: var(--svg-opacity--0-28, 0.28);
}

.vygbsf0hk {
  d: path("M5.66 46.65c-4.25 10.35.22 21.01 4.41 25.5c.57.62 3.01 3.01 3.57 4.92c0 0 9.54-13.31 12.39-21.13c.58-1.58 1.1-3.2 1.17-4.88c.05-1.26-.14-2.76-.87-3.83c-.89-1.31-1.93-.96-3.44-.96c-2.88 0-15.49-.74-16.47-.74c.01.02-.76 1.12-.76 1.12");
}

.yl8ecwbsj {
  d: path("M102.6 73.69c-.03-.9-.73-1.63-1.63-1.69l-12.72-.76c-.93-.07-1.75.61-1.86 1.54L75.58 124h28.93z");
}

.ze8v-0bag {
  d: path("M63.41 5.47c7.32 1.98 10.89 5.71 12.08 10.68c.35 1.46.77 15.08-25.23-.4c-9.67-5.76-7.03-9.36-5.9-9.77c4.42-1.6 10.85-2.73 19.05-.51");
}

</style>
