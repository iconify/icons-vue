<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="fbc1i5c8q"/><path class="uvi-ntave"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pundix-background" /></template>
<style>
.fbc1i5c8q {
  fill: var(--svg-color--f2d30e, #f2d30e);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.uvi-ntave {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 5.143L5.143 4l6.286 6.286l-1.143 1.143zm8.571 8.571l1.143-1.143L20 18.857L18.857 20zM10.857 12L12 10.857L13.143 12L12 13.143zm1.714-1.714L18.857 4L20 5.143l-6.286 6.286zM4 18.857l6.286-6.286l1.143 1.143L5.143 20z");
}

</style>
