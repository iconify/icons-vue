<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<ellipse class="dh2blbell"/><path class="h7xa9wfvl"/><path class="yz1yci-gp"/><ellipse class="nwh6hsxss"/><ellipse class="tf1z14ucm"/><path class="rz-0ubc0l"/><path class="s15ftlbtr"/><path class="h6dj8vknf"/><circle class="ris607gop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:womans-hat" /></template>
<style>
.dh2blbell {
  cx: 18px;
  cy: 23px;
  fill: var(--svg-color--ffd983, #ffd983);
  rx: 18px;
  ry: 5px;
}

.h6dj8vknf {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.172 19.587c-.782-.782-1.098-1.732-.707-2.122c.391-.391 1.34-.074 2.121.707c.781.782 1.098 1.73.707 2.121c-.391.392-1.341.074-2.121-.706m4.242 4.242c-.782-.78-1.098-1.73-.707-2.121c.391-.392 1.34-.074 2.121.707s1.098 1.73.707 2.121c-.389.39-1.34.074-2.121-.707");
}

.h7xa9wfvl {
  fill: var(--svg-color--ffd983, #ffd983);
  d: path("M29 17c0 1.566-4.925 6-11 6S7.043 18.566 7.043 17C7.043 10 14 7 18 7s11 3 11 10");
}

.nwh6hsxss {
  cx: 18px;
  cy: 24px;
  fill: var(--svg-color--fff, #fff);
  rx: 1px;
  ry: 2px;
}

.ris607gop {
  cx: 18px;
  cy: 21px;
  r: 2px;
  fill: var(--svg-color--ffac33, #ffac33);
}

.rz-0ubc0l {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.586 23.828c-.781.781-1.731 1.098-2.121.707c-.391-.391-.074-1.34.707-2.121s1.73-1.098 2.122-.707c.39.391.073 1.341-.708 2.121m4.242-4.242c-.78.781-1.73 1.098-2.121.707s-.074-1.34.707-2.122s1.73-1.098 2.121-.707s.074 1.341-.707 2.122");
}

.s15ftlbtr {
  fill: var(--svg-color--fff, #fff);
  d: path("M15 22c-1.105 0-2-.448-2-1c0-.553.896-1 2-1s2 .447 2 1s-.896 1-2 1m6 0c-1.104.001-2-.447-2-1s.896-1 2-1s2 .447 2 1s-.896 1-2 1");
}

.tf1z14ucm {
  cx: 18px;
  cy: 18px;
  fill: var(--svg-color--fff, #fff);
  rx: 1px;
  ry: 2px;
}

.yz1yci-gp {
  fill: var(--svg-color--9266cc, #9266cc);
  d: path("M29 21c-5 3-17 3-22 0c0-.492.043-3.535.043-4C13 20 23 20 29 17c-.003.465 0 3.508 0 4");
}

</style>
