<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s9r86sbju"/><path class="et5uh2j5y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:video-tour" /></template>
<style>
.et5uh2j5y {
  d: path("M15.5 6.5v-3H18v5M7 21v-3.5a2 2 0 0 1 4 0V21m6.211-5.309l1.836.988a1.5 1.5 0 0 1 0 2.642l-1.836.988A1.5 1.5 0 0 1 15 18.989v-1.978a1.5 1.5 0 0 1 2.211-1.32");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s9r86sbju {
  d: path("M12.636 21H5.625q-.129 0-.257-.013q-.129-.012-.255-.037q-.127-.026-.25-.063T4.62 20.8q-.119-.049-.232-.11t-.221-.132t-.207-.154t-.191-.173q-.091-.091-.173-.191q-.082-.099-.154-.207q-.071-.107-.132-.221q-.061-.113-.11-.232q-.05-.12-.087-.243t-.063-.25q-.025-.126-.037-.255Q3 18.504 3 18.375v-6.146q0-.289.063-.57q.063-.282.185-.543q.123-.261.299-.49t.398-.413L10.32 4.9q.088-.073.181-.138q.094-.065.193-.122t.202-.105t.211-.086q.107-.039.217-.068t.223-.05q.112-.019.225-.029q.114-.01.228-.01t.228.01q.113.01.225.029q.113.02.223.05q.11.029.217.068q.108.038.211.086t.202.105t.193.122t.181.138l6.375 5.313q.222.185.398.413q.176.229.299.49q.122.261.185.543q.063.281.063.57v2.403");
}

</style>
