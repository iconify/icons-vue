<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="ej3px2bko"/><path class="jb1_7xkrm"/><path class="b7w6m-pog"/><path class="mdidvobnx"/><circle class="fxshxhxpf"/><circle class="tm5cxy95l"/><ellipse class="fvweb2bgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:wind-chime" /></template>
<style>
.b7w6m-pog {
  fill: var(--svg-color--77b255, #77b255);
  d: path("M26 10c0 4.418-3.582 5-8 5s-8-.582-8-5a8 8 0 0 1 16 0");
}

.ej3px2bko {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M17 36c-1.32 0-9.241-.826-10.707-2.293a.997.997 0 0 1 .177-1.554c4.563-2.853 6.825-7.969 6.541-14.796A10 10 0 0 1 13 17a1 1 0 0 1 1-1h9a1 1 0 0 1 .997.923c.841 10.931-2.468 15.783-3.93 17.361C19.043 35.391 17.954 36 17 36");
}

.fvweb2bgy {
  cx: 14px;
  cy: 32.5px;
  fill: var(--svg-color--fff, #fff);
  rx: 2px;
  ry: 1.5px;
}

.fxshxhxpf {
  cx: 18px;
  cy: 21px;
  r: 2px;
  fill: var(--svg-color--fff, #fff);
}

.jb1_7xkrm {
  fill: var(--svg-color--3e721d, #3e721d);
  d: path("M18 18a1 1 0 0 1-1-1v-3a1 1 0 0 1 2 0v3a1 1 0 0 1-1 1");
}

.mdidvobnx {
  fill: var(--svg-color--3e721d, #3e721d);
  d: path("M18 4a1 1 0 0 1-1-1V1a1 1 0 0 1 2 0v2a1 1 0 0 1-1 1");
}

.tm5cxy95l {
  cx: 17px;
  cy: 27px;
  r: 2px;
  fill: var(--svg-color--fff, #fff);
}

</style>
