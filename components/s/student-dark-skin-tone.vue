<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ec9ovvkxu"/><radialGradient id="SVGn5Lxre0q" cx="99.638" cy="82.059" r="23.419" gradientTransform="matrix(1 0 0 -.4912 -21.055 122.366)" gradientUnits="userSpaceOnUse"><stop offset=".728" class="qpo2vg_rh"/><stop offset="1" class="g00j4bcaa"/></radialGradient><path fill="url(#SVGn5Lxre0q)" class="zzpq50b6f"/><radialGradient id="SVGkaQqyO3h" cx="76.573" cy="78.577" r="6.921" gradientTransform="rotate(154.924 73.891 12.931)scale(1 -.7418)" gradientUnits="userSpaceOnUse"><stop offset=".663" class="g00j4bcaa"/><stop offset="1" class="qpo2vg_rh"/></radialGradient><path fill="url(#SVGkaQqyO3h)" class="o5vaqcbhp"/><radialGradient id="SVGhepeecCw" cx="94.509" cy="58.998" r="30.399" gradientTransform="matrix(-.0746 -.9972 -.8311 .0622 139.799 149.575)" gradientUnits="userSpaceOnUse"><stop offset=".725" class="qpo2vg_rh"/><stop offset="1" class="g00j4bcaa"/></radialGradient><path fill="url(#SVGhepeecCw)" class="lz8w4779g"/><radialGradient id="SVGLRUFvcbs" cx="44.31" cy="58.998" r="30.399" gradientTransform="matrix(.0746 -.9972 .8311 .0622 -8.03 99.516)" gradientUnits="userSpaceOnUse"><stop offset=".725" class="qpo2vg_rh"/><stop offset="1" class="g00j4bcaa"/></radialGradient><path fill="url(#SVGLRUFvcbs)" class="a7jlroqgw"/><radialGradient id="SVGtP7gQcxX" cx="49.439" cy="82.059" r="23.419" gradientTransform="matrix(-1 0 0 -.4912 98.878 122.366)" gradientUnits="userSpaceOnUse"><stop offset=".728" class="qpo2vg_rh"/><stop offset="1" class="g00j4bcaa"/></radialGradient><path fill="url(#SVGtP7gQcxX)" class="x1kw994zl"/><radialGradient id="SVGo2g3WbBY" cx="26.374" cy="78.577" r="6.921" gradientTransform="rotate(25.076 -19.233 68.434)scale(1 .7418)" gradientUnits="userSpaceOnUse"><stop offset=".663" class="g00j4bcaa"/><stop offset="1" class="qpo2vg_rh"/></radialGradient><path fill="url(#SVGo2g3WbBY)" class="gnf1dbbsj"/><path class="jrwhlck8s"/><path class="xdm-vz3fo"/><radialGradient id="SVGxTdVmatN" cx="63.995" cy="122.603" r="54.172" gradientTransform="matrix(1 0 0 .5247 0 58.274)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="wk_lp_wlk"/><stop offset="1" class="aplh-7tkj"/></radialGradient><path fill="url(#SVGxTdVmatN)" class="ba5mhrsid"/><path class="sgbca8pwj"/><path class="wsh3umkci"/><path class="e_sci2b-g"/><g class="d2ol71wkq"><ellipse class="qvgrblbah"/><ellipse class="ih3uzb6nu"/></g><path class="enoehrk_z"/><path class="ycn8nq24t"/><path class="exw2pvbgy"/><radialGradient id="SVGwznFOdCo" cx="82.872" cy="43.464" r="33.876" gradientTransform="matrix(.3076 .9515 -.706 .2282 88.065 -45.31)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="qpo2vg_rh"/><stop offset="1" class="g00j4bcaa"/></radialGradient><path fill="url(#SVGwznFOdCo)" class="hk_1fg_yd"/><radialGradient id="SVG5YIX3cZv" cx="38.533" cy="43.3" r="16.886" gradientTransform="rotate(7.833 166.69 52.084)scale(1 1.4052)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="qpo2vg_rh"/><stop offset="1" class="g00j4bcaa"/></radialGradient><path fill="url(#SVG5YIX3cZv)" class="sv_yerkth"/><radialGradient id="SVG77TjkcSB" cx="37.086" cy="32.223" r="12.941" gradientTransform="matrix(-.9657 -.2598 .2432 -.9037 65.062 70.978)" gradientUnits="userSpaceOnUse"><stop offset=".66" class="qpo2vg_rh"/><stop offset="1" class="g00j4bcaa"/></radialGradient><path fill="url(#SVG77TjkcSB)" class="mv27p5blj"/><path class="bgdwpgjuf"/><path class="ntfdk_bte"/><ellipse class="vqkmvy6ev"/><path class="y_8brbcey"/><linearGradient id="SVGMDk4mcBw" x1="63.42" x2="63.42" y1="-.333" y2="28.307" gradientUnits="userSpaceOnUse"><stop offset=".003" class="a72as_i6q"/><stop offset=".472" class="d_wzpg_av"/><stop offset="1" class="wk_lp_wlk"/></linearGradient><path fill="url(#SVGMDk4mcBw)" class="zmux6668o"/><linearGradient id="SVGzL0zWbcL" x1="63.42" x2="63.42" y1="-.167" y2="30.833" gradientUnits="userSpaceOnUse"><stop offset=".003" class="aplh-7tkj"/><stop offset=".324" class="a0m3qtb0g"/><stop offset=".955" class="osi2yu8vz"/><stop offset="1" class="wk_lp_wlk"/></linearGradient><path fill="url(#SVGzL0zWbcL)" class="gt39xwb5b"/><linearGradient id="SVG8EaMaetV" x1="13.309" x2="114.137" y1="18" y2="18" gradientUnits="userSpaceOnUse"><stop offset=".001" class="fy7ry9ban"/><stop offset=".3" class="gjuor2bpt"/><stop offset=".7" class="gjuor2bpt"/><stop offset="1" class="fy7ry9ban"/></linearGradient><path fill="url(#SVG8EaMaetV)" class="rmht3mbyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:student-dark-skin-tone" /></template>
<style>
.a0m3qtb0g {
  stop-color: var(--svg-color--505050, #505050);
}

.a72as_i6q {
  stop-color: var(--svg-color--424242, #424242);
}

.a7jlroqgw {
  d: path("M21.4 46.56c-4.25 10.35.22 21.01 4.41 25.51c.58.62 3.01 3.01 3.57 4.92c0 0 9.54-13.31 12.39-21.13c.58-1.58 1.1-3.2 1.17-4.88c.05-1.26-.14-2.76-.87-3.83c-.89-1.31-1.93-.96-3.44-.96c-2.88 0-15.49-.74-16.47-.74c.01.01-.76 1.11-.76 1.11");
}

.aplh-7tkj {
  stop-color: var(--svg-color--616161, #616161);
}

.ba5mhrsid {
  d: path("M114.5 120.99c0-14.61-21.75-21.54-40.72-23.1l-8.6 11.03c-.28.36-.72.58-1.18.58s-.9-.21-1.18-.58L54.2 97.87c-10.55.81-40.71 4.75-40.71 23.12V124h101z");
}

.bgdwpgjuf {
  fill: var(--svg-color--e8ad00, #e8ad00);
  d: path("M14.74 53.3c-1.24 0-2.25.96-2.25 2.14v9.2c0 1.18 1.01 2.14 2.25 2.14s2.25-.96 2.25-2.14v-9.2c0-1.18-1.01-2.14-2.25-2.14m-4.5 0c-1.24 0-2.25.96-2.25 2.14v9.2c0 1.18 1.01 2.14 2.25 2.14s2.25-.96 2.25-2.14v-9.2c0-1.18-1.01-2.14-2.25-2.14");
}

.d_wzpg_av {
  stop-color: var(--svg-color--353535, #353535);
}

.d2ol71wkq {
  fill: var(--svg-color--1a1717, #1a1717);
}

.e_sci2b-g {
  fill: var(--svg-color--1a1717, #1a1717);
  d: path("M54.8 49.72c-.93-1.23-3.07-3.01-7.23-3.01s-6.31 1.79-7.23 3.01c-.41.54-.31 1.17-.02 1.55c.26.35 1.04.68 1.9.39s2.54-1.16 5.35-1.18c2.81.02 4.49.89 5.35 1.18s1.64-.03 1.9-.39c.28-.37.39-1-.02-1.55m32.87 0c-.93-1.23-3.07-3.01-7.23-3.01s-6.31 1.79-7.23 3.01c-.41.54-.31 1.17-.02 1.55c.26.35 1.04.68 1.9.39s2.54-1.16 5.35-1.18c2.81.02 4.49.89 5.35 1.18s1.64-.03 1.9-.39c.28-.37.39-1-.02-1.55");
}

.ec9ovvkxu {
  fill: var(--svg-color--232020, #232020);
  d: path("M98.9 79.76c-1.25-2.27.34-4.58 3.06-7.44c4.31-4.54 9-15.07 4.64-25.76c.03-.06-.86-1.86-.83-1.92l-1.79-.09c-.57-.08-20.26-.12-39.97-.12s-39.4.04-39.97.12c0 0-2.65 1.95-2.63 2.01c-4.35 10.69.33 21.22 4.64 25.76c2.71 2.86 4.3 5.17 3.06 7.44c-1.21 2.21-4.81 2.53-4.81 2.53s.83 2.26 2.83 3.48c1.85 1.13 4.13 1.39 5.7 1.43c0 0 6.15 8.51 22.23 8.51h17.9c16.08 0 22.23-8.51 22.23-8.51c1.57-.04 3.85-.3 5.7-1.43c2-1.22 2.83-3.48 2.83-3.48s-3.61-.33-4.82-2.53");
}

.enoehrk_z {
  fill: var(--svg-color--1a1717, #1a1717);
  d: path("M72.42 76.05c-3.18 1.89-13.63 1.89-16.81 0c-1.83-1.09-3.7.58-2.94 2.24c.75 1.63 6.44 5.42 11.37 5.42s10.55-3.79 11.3-5.42c.75-1.66-1.09-3.33-2.92-2.24");
}

.exw2pvbgy {
  fill: var(--svg-color--232020, #232020);
  d: path("M99.27 23.45c-.79-4.72-13.85-13.12-18.74-14.67c-13.24-4.19-21.85-2.49-26.47.03c-.96.52-7.17 3.97-11.51 1.5c-2.72-1.55-10.53 10.84-14.46 13.21c-4.59 2.77-4.19 7.81-3.49 9.77c-2.52 2.14-5.69 6.69-3.52 12.6c1.64 4.45 8.17 6.5 8.17 6.5c-.62 10.74 2.28 15.95 2.28 15.95s4.69-18.45 4.3-21.27c0 0 7.76-1.54 16.57-6.58c5.95-3.41 10.02-7.4 16.71-8.91c10.18-2.29 12.45 5.08 12.45 5.08s9.42-1.81 12.26 11.27c1.17 5.38 1.93 14.3 2.57 19.77c-.06-.48 3.24-6.33 3.86-12.33c.16-1.55 4.34-3.6 6.14-10.26c2.4-8.88-.24-18.5-7.12-21.66");
}

.fy7ry9ban {
  stop-color: var(--svg-color--bfbebe, #bfbebe);
}

.g00j4bcaa {
  stop-color: var(--svg-color--444140, #444140);
}

.gjuor2bpt {
  stop-color: var(--svg-color--212121, #212121);
  stop-opacity: 0;
}

.gnf1dbbsj {
  d: path("M32.92 83.07c4.28-6.5-5.21-8.93-5.21-8.93l-.01.01c1.65 2.05 2.4 3.84 1.43 5.61c-1.21 2.21-4.81 2.53-4.81 2.53s4.91 4.36 8.6.78");
}

.gt39xwb5b {
  d: path("M63.42 4s-21.17.25-52 8c0 0 35.41 9.67 52 9.38c16.59.29 52-9.38 52-9.38c-30.84-7.75-52-8-52-8");
}

.hk_1fg_yd {
  d: path("M106.4 45.1c-1.5 5.53-4.63 7.88-5.75 9.41c-1.54-9.37-1.3-18.27-12.71-28.81c0 0 2.29-.49 3.41-2.53c.87-1.59.54-3.57.54-3.57c.38.02.77.06 1.17.11c1.96.36 3.96 1.32 5.79 2.55c.22.42.36.82.42 1.19c6.88 3.15 9.53 12.77 7.13 21.65");
}

.ih3uzb6nu {
  cx: 80.44px;
  cy: 58.72px;
  rx: 4.93px;
  ry: 5.1px;
}

.jrwhlck8s {
  fill: var(--svg-color--3c2b24, #3c2b24);
  d: path("M73.78 112.04V89.25H54.21v22.79z");
}

.lz8w4779g {
  d: path("M106.62 46.56c4.25 10.35-.22 21.01-4.41 25.51c-.57.62-3.01 3.01-3.57 4.92c0 0-9.54-13.31-12.39-21.13c-.57-1.58-1.1-3.2-1.17-4.88c-.05-1.26.14-2.76.87-3.83c.89-1.31 20.16-1.7 20.16-1.7c0 .01.51 1.11.51 1.11");
}

.mv27p5blj {
  d: path("M32.69 30.9v-.05c-3.03 0-5.93.91-7.82 2.21c0 .03-.15.14-.27.23v-.01c.01-.01.03-.02.04-.03c-.7-1.96-1.11-7 3.49-9.77c.44-.27.93-.66 1.46-1.15c1.22-.5 2.52-.79 3.72-.91c.35-.03.99-.08 1.18-.08l4.81.59z");
}

.ntfdk_bte {
  fill: var(--svg-color--ffca28, #ffca28);
  d: path("M12.49 53.3c-1.24 0-2.25.96-2.25 2.14v11.19c0 1.18 1.01 2.14 2.25 2.14s2.25-.96 2.25-2.14V55.44c0-1.18-1.01-2.14-2.25-2.14");
}

.o5vaqcbhp {
  d: path("M95.1 83.07c-4.28-6.5 5.21-8.93 5.21-8.93l.01.01c-1.65 2.05-2.4 3.84-1.43 5.61c1.21 2.21 4.81 2.53 4.81 2.53s-4.91 4.36-8.6.78");
}

.osi2yu8vz {
  stop-color: var(--svg-color--242424, #242424);
}

.qpo2vg_rh {
  stop-color: var(--svg-color--444140, #444140);
  stop-opacity: 0;
}

.qvgrblbah {
  cx: 47.56px;
  cy: 58.72px;
  rx: 4.93px;
  ry: 5.1px;
}

.rmht3mbyx {
  d: path("M115.42 12c-30.83-7.75-52-8-52-8s-21.17.25-52 8v.77c0 1.33.87 2.5 2.14 2.87c3.72 1.1 11.47 3.34 16.53 4.36c0 0-1.11 1.71-2 3.52c0 0 9.95 5.92 35.33 8.48c25.38-2.56 35.85-8.55 35.85-8.55c-.88-1.81-1.98-3.45-1.98-3.45c4.5-.74 12.32-3.14 16.04-4.32c1.25-.4 2.09-1.55 2.09-2.86z");
  opacity: var(--svg-opacity--0-4, 0.4);
}

.sgbca8pwj {
  fill: var(--svg-color--3c2b24, #3c2b24);
  d: path("M91.33 50.34H36.67c-5.89 0-10.71 5.13-10.71 11.41s4.82 11.41 10.71 11.41h54.65c5.89 0 10.71-5.14 10.71-11.41c.01-6.27-4.81-11.41-10.7-11.41");
}

.sv_yerkth {
  d: path("M24.37 33.49c-2.37 2.1-5.56 6.79-3.21 12.61c1.77 4.39 8.09 6.29 8.09 6.29c0 .02 1.26.4 1.91.4l1.48-21.9c-3.03 0-5.94.91-7.82 2.22c.03.03-.46.35-.45.38");
}

.vqkmvy6ev {
  cx: 12.49px;
  cy: 52.07px;
  fill: var(--svg-color--ffca28, #ffca28);
  rx: 2.76px;
  ry: 2.63px;
}

.wk_lp_wlk {
  stop-color: var(--svg-color--212121, #212121);
}

.wsh3umkci {
  fill: var(--svg-color--70534a, #70534a);
  d: path("M64 10.98c-17.4 0-33.52 18.61-33.52 45.4c0 26.64 16.61 39.81 33.52 39.81s33.52-13.17 33.52-39.81c0-26.79-16.12-45.4-33.52-45.4");
}

.x1kw994zl {
  d: path("M64.03 95.7v-9.44L35.46 84l-2.6 3.2s6.15 8.51 22.23 8.51z");
}

.xdm-vz3fo {
  fill: var(--svg-color--212121, #212121);
  d: path("M114.5 120.99c0-14.61-21.75-21.54-40.72-23.1l-8.6 11.03c-.28.36-.72.58-1.18.58s-.9-.21-1.18-.58L54.2 97.87c-10.55.81-40.71 4.75-40.71 23.12V124h101z");
}

.y_8brbcey {
  fill: var(--svg-color--504f4f, #504f4f);
  d: path("M12.49 52.04c-.55 0-1-.45-1-1v-38c0-.55.45-1 1-1s1 .45 1 1v38c0 .55-.45 1-1 1");
}

.ycn8nq24t {
  fill: var(--svg-color--33251f, #33251f);
  d: path("M67.86 67.96c-.11-.04-.21-.07-.32-.08h-7.08c-.11.01-.22.04-.32.08c-.64.26-.99.92-.69 1.63s1.71 2.69 4.55 2.69s4.25-1.99 4.55-2.69s-.05-1.37-.69-1.63");
}

.zmux6668o {
  d: path("M115.42 12c-30.83-7.75-52-8-52-8s-21.17.25-52 8v.77c0 1.33.87 2.5 2.14 2.87c3.72 1.1 11.47 3.34 16.53 4.36c0 0-1.11 1.71-2 3.52c0 0 9.95 5.92 35.33 8.48c25.38-2.56 35.85-8.55 35.85-8.55c-.88-1.81-1.98-3.45-1.98-3.45c4.5-.74 12.32-3.14 16.04-4.32c1.25-.4 2.09-1.55 2.09-2.86z");
}

.zzpq50b6f {
  d: path("M63.99 95.7v-9.44L92.56 84l2.6 3.2s-6.15 8.51-22.23 8.51z");
}

</style>
