<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="l5506epvj"/><path clip-rule="evenodd" class="qpuuw4bqa"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:twt-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.l5506epvj {
  fill: var(--svg-color--3274c0, #3274c0);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qpuuw4bqa {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M5.212 6.547c.012 2.977.036 8.007 1.2 9.515c1.256 1.628 3.025 2.605 4.235 3.271c.398.22.736.407.974.572c.172.119.424.13.596.011c.335-.232.814-.5 1.352-.8c1.394-.781 3.185-1.784 3.887-2.952c1.05-1.744 1.256-6.514 1.332-9.57a.57.57 0 0 0-.58-.574c-2.52.014-4.737-.921-5.837-1.855a.68.68 0 0 0-.858-.023c-1.857 1.531-4.118 1.81-5.757 1.85a.556.556 0 0 0-.544.555m1.697 1.05c.012 2.105.214 6.588.93 7.67c.574.867 1.943 1.568 2.958 2.09c.572.292 1.031.528 1.177.704c.229-.215.709-.473 1.27-.774c.997-.535 2.25-1.208 2.806-2.02c.629-.918.993-5.468 1.04-7.67c-2.335.15-4.384-1.042-5.116-1.658c-1.48 1.244-3.994 1.623-5.065 1.657");
}

</style>
