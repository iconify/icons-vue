<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hz0mxk71c"/><path class="zvs08ob7l"/><path class="is17_8b8g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:reverse-mortgage" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hz0mxk71c {
  d: path("M18.716 20.978q-.17.022-.341.022H5.625q-.129 0-.257-.013q-.129-.012-.255-.037q-.127-.026-.25-.063T4.62 20.8q-.119-.049-.232-.11t-.221-.132t-.207-.154t-.191-.173q-.091-.091-.173-.191q-.082-.099-.154-.207q-.071-.107-.132-.221q-.061-.113-.11-.232q-.05-.12-.087-.243t-.063-.25q-.025-.126-.037-.255Q3 18.504 3 18.375v-6.646q0-.289.063-.57q.063-.282.185-.543q.123-.261.299-.49t.398-.413L10.32 4.4q.088-.073.181-.138q.094-.065.193-.122t.202-.105t.211-.086q.107-.039.217-.068t.223-.05q.112-.019.225-.029q.114-.01.228-.01t.228.01q.113.01.225.029q.113.02.223.05q.11.029.217.068q.108.038.211.086t.202.105t.193.122t.181.138l6.375 5.313q.222.185.398.413q.176.229.299.49q.122.261.185.543q.063.281.063.57v2.303");
}

.is17_8b8g {
  d: path("M16.75 14.75L15 16.5l1.75 1.75");
}

.zvs08ob7l {
  d: path("M7 21v-3.5a2 2 0 0 1 4 0V21m10.5.5V19a2.5 2.5 0 0 0-2.5-2.5h-4");
}

</style>
