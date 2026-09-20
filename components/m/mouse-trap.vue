<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<linearGradient id="SVGoQSmFeFq" x1="55.803" x2="55.803" y1="101.263" y2="122.806" gradientUnits="userSpaceOnUse"><stop offset="0" class="sll_zg-uo"/><stop offset="1" class="k05n1gbkm"/></linearGradient><path fill="url(#SVGoQSmFeFq)" class="e136u6bdd"/><path class="lyle_obtb"/><path class="x3xi5rppn"/><path class="lei5ovb9u"/><path class="frxkhn8ug"/><path class="taro1ehhw"/><path class="xgbt6f_yk"/><path class="sn_4dv4fb"/><path class="hh8g_gbtr"/><path class="ca6j80xvs"/><ellipse transform="rotate(-21.801 60.33 91.149)" class="ih34zxbyi"/><radialGradient id="SVG83Migcdp" cx="78.391" cy="34.145" r="6.257" gradientTransform="rotate(183.308 .959 61.964)scale(-1 1)" gradientUnits="userSpaceOnUse"><stop offset=".165" class="sxfysoqtr"/><stop offset="1" class="e3zl1gbje"/></radialGradient><path fill="url(#SVG83Migcdp)" class="w80o3lbvo"/><ellipse transform="rotate(-1.828 68.436 103.594)" class="i-i-vpb6c"/><path class="cggwc1u0a"/><path class="gnatf5ifs"/><path class="doihsibza"/><path class="v9bxzqb0c"/><path class="lcq4wqb-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:mouse-trap" /></template>
<style>
.ca6j80xvs {
  fill: var(--svg-color--ffe959, #ffe959);
  d: path("M87.35 88.13c-.04-1.16-1.19-1.95-2.28-1.56l-34.18 16.01c-.71.25-1.17.93-1.15 1.67l.41 12.93c.04 1.16 1.19 1.95 2.28 1.56l25.47-11.93c.38-.18.63-.55.65-.98c.06-1.1.41-3.16 2.21-3.17c.83-.01 1.41.51 1.76.98c.32.43.9.58 1.39.35l2.7-1.27c.71-.25 1.17-.93 1.15-1.68z");
}

.cggwc1u0a {
  fill: var(--svg-color--4e342e, #4e342e);
  d: path("M20.29 33.8c.73-.2 2.38-.05 3.38 1.34c1.25 1.72.19 5.84 2.02 8.56c1.03 1.52 2.61 1.81 2.61 1.81c-1.13.16-7.23 1.84-8.25-4.61");
}

.doihsibza {
  fill: var(--svg-color--ba793e, #ba793e);
  d: path("M29.65 47.63c.6 1.42-.72 2.51-.72 2.51c2.7-.67 4.7-2.33 5.96-4.62l-9.27.07c0-.01 3.13-.1 4.03 2.04");
}

.e136u6bdd {
  d: path("M105.24 101.72H44.21L6.58 121.47c-.37.19-.23.76.19.76h18.12l-1.47 1.97s.33.03 1.75-.19c1.42-.23 4.09-1.77 4.09-1.77H64.5c.43 0 .86-.1 1.24-.3z");
}

.e3zl1gbje {
  stop-color: var(--svg-color--f19534, #f19534);
}

.frxkhn8ug {
  fill: var(--svg-color--d68b52, #d68b52);
  d: path("M4 43.5L28.91 5.33h58.22L65.03 43.5z");
}

.gnatf5ifs {
  fill: var(--svg-color--ffb74d, #ffb74d);
  d: path("M25.62 45.58c-3.21-1.08-4.11-4.99-3.85-7.26c.4-3.36-.72-4.07-1.55-4.33c-2.75-.89-4.77 1.33-4.77 6.55c0 6.42 5.67 8.68 5.67 8.73v73.7c0 .25.12.48.33.62c.38.25 1.06.6 1.97.6s1.62-.35 2.01-.61c.21-.14.34-.38.34-.63V50.57c.22.01 6.23.2 9.12-5.05z");
}

.hh8g_gbtr {
  fill: var(--svg-color--ffc107, #ffc107);
  d: path("M87.35 88.13c-.09-1.36-.47-3.36-4.47-3.36l-10.24-.1c-.24 0-.46.13-.54.36c-.16.48-.45.92-.86 1.29c-1.22 1.09-3.03 1.04-4.04-.1c-.31-.34-.5-.75-.59-1.18a.566.566 0 0 0-.55-.44l-5.94-.06c-1.02-.01-1.96.54-2.45 1.44l-9.09 16.78c-.25.4-.38.87-.37 1.34l.4 12.59c.05 1.59 1.56 2.76 3.82 2.05L87.65 97.5z");
}

.i-i-vpb6c {
  cx: 68.436px;
  cy: 103.594px;
  fill: var(--svg-color--ffc107, #ffc107);
  rx: 2.9px;
  ry: 3.41px;
}

.ih34zxbyi {
  cx: 60.33px;
  cy: 91.149px;
  fill: var(--svg-color--f19534, #f19534);
  rx: 2.96px;
  ry: 2.16px;
}

.k05n1gbkm {
  stop-opacity: 0;
}

.lcq4wqb-n {
  fill: var(--svg-color--868789, #868789);
  d: path("M23.38 93.272c-1.173 0-2.074-.397-2.502-.65c-.376-.222-.777-.58-.777-1.269c0-1.285.989-1.43.989-1.43c.119.413.55 1.35 2.29 1.35s2.249-.76 2.39-1.375c0 0 1.039.167 1.039 1.407c0 .426-.265.94-1.039 1.385c-.587.34-1.366.582-2.39.582");
}

.lei5ovb9u {
  fill: var(--svg-color--a06841, #a06841);
  d: path("m63.96 45.55l37.37 54.12H45.28L7.91 45.55zm1.07-2.05H4l40.21 58.22h61.03z");
}

.lyle_obtb {
  fill: var(--svg-color--5d4037, #5d4037);
  d: path("M105.24 101.72H44.21L4 43.5h61.03z");
}

.sll_zg-uo {
  stop-opacity: 0.5;
}

.sn_4dv4fb {
  fill: var(--svg-color--d1762c, #d1762c);
  d: path("M64.75 84.6h1.31c.31 0 .62.11.85.32l3.36 2.88l-4.15.55z");
}

.sxfysoqtr {
  stop-color: var(--svg-color--ffc107, #ffc107);
}

.taro1ehhw {
  fill: var(--svg-color--a06841, #a06841);
  d: path("M87.13 5.33C87.45 6.3 124 60.64 124 60.64l-18.76 41.08L65.03 43.5z");
}

.v9bxzqb0c {
  fill: var(--svg-color--868789, #868789);
  d: path("M4 115.066v-2.521c7.603-4.199 14.71-12.022 16.956-20.411l1.931.517c-2.382 8.905-10.62 18.102-18.887 22.415");
}

.w80o3lbvo {
  d: path("M79.43 89.2s1.25 5.68-2.44 6.67c-3.26.87-3.88-3.41-3.88-3.41s-3.87-1.64-1.25-2.86c4.12-1.92 7.57-.4 7.57-.4");
}

.x3xi5rppn {
  fill: var(--svg-color--3e2723, #3e2723);
  d: path("m48.22 38.67l14.75 21.97l-18.76 41.08h61.03l-1.86-63.15z");
}

.xgbt6f_yk {
  fill: var(--svg-color--f19534, #f19534);
  d: path("M77.12 104.56c.14 0 3.3.05 4.88-.1s2.62-.79 2.62-.79L78.5 99.5z");
}

</style>
