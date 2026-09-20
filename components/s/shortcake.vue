<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<ellipse class="orh-81b6x"/><ellipse class="zz307pbga"/><ellipse class="nkq_v_dwq"/><path class="u93utfrpk"/><path class="q5hswtzqj"/><path class="xl--ui14d"/><path class="hw3tpcbaq"/><path class="u2qqzabeq"/><path class="v4d4irbmp"/><path class="yis9leamn"/><path class="gw7-x4bif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:shortcake" /></template>
<style>
.gw7-x4bif {
  fill: var(--svg-color--f4abba, #f4abba);
  d: path("M18.375 5.042a.5.5 0 0 1-.4-.2l-.5-.667a.5.5 0 1 1 .8-.6l.5.667a.5.5 0 0 1-.4.8m-2.416 3.5a.5.5 0 0 1-.484-.626l.25-.958a.5.5 0 0 1 .967.253l-.25.958a.5.5 0 0 1-.483.373m4.374.083a.5.5 0 0 1-.261-.073l-.75-.458a.501.501 0 0 1 .522-.854l.75.458a.501.501 0 0 1-.261.927");
}

.hw3tpcbaq {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M8 21v-1l21-4v1z");
}

.nkq_v_dwq {
  cx: 18px;
  cy: 22.611px;
  fill: var(--svg-color--fff, #fff);
  rx: 14.8px;
  ry: 7.611px;
}

.orh-81b6x {
  cx: 18px;
  cy: 25px;
  fill: var(--svg-color--939598, #939598);
  rx: 18px;
  ry: 10px;
}

.q5hswtzqj {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M8 27V15s21-7 21-2.458V23z");
}

.u2qqzabeq {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("m8 14l9-9c2 0 8 1 11 5z");
}

.u93utfrpk {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M8 28c0-3.044.417-7.208.042-13.875c.601-1.377 6.146-2.472 6.625-3.792C15.954 6.787 13.458 4.417 16 2c2.05-1.949 5-2 6 1c2-2 6-1 6 2c4-1 6 3 3 6c0 1-1 9-1 11s-.208 1.792-5.208 2.792S8 28 8 28");
}

.v4d4irbmp {
  fill: var(--svg-color--fff, #fff);
  d: path("M30 10c1-1 1-5-3-4c0-1-2-4-5-2c0-1-5-2-6 0c10 3 14 6 14 6");
}

.xl--ui14d {
  fill: var(--svg-color--ffd983, #ffd983);
  d: path("M8 26V16s12.375-4.208 20-4v10z");
}

.yis9leamn {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M17.958 10.458c-1.833-.208-4.417-1.083-3.917-3.5s2.474-4.881 3.75-5.542C18.917.833 20.117 1.26 21 4.667c.583 2.25 2.75 5.125-1.667 5.75c-.458 0-1.375.041-1.375.041");
}

.zz307pbga {
  cx: 18px;
  cy: 23px;
  fill: var(--svg-color--f1f2f2, #f1f2f2);
  rx: 18px;
  ry: 10px;
}

</style>
