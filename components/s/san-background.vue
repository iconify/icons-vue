<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ezpmtcbhb"/><path class="w-le59bps"/><path clip-rule="evenodd" class="x6t1a5bqg"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:san-background" /></template>
<style>
.ezpmtcbhb {
  fill: var(--svg-color--2b77b3, #2b77b3);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.w-le59bps {
  fill: var(--svg-color--fff, #fff);
  d: path("m13.948 8.53l-.291.944c-.553-.087-1.07-.196-1.585-.247c-.306-.029-.627.051-.742.393c-.124.357-.139.728.152 1.004c.306.284.655.51.99.75c.305.232.632.436.902.697c.72.728.843 1.6.552 2.547a1.8 1.8 0 0 1-1.127 1.134a3.7 3.7 0 0 1-2.983-.356l.342-.99c.502.131.953.291 1.418.364c.444.073.91 0 1.143-.458a1.09 1.09 0 0 0-.204-1.31c-.277-.283-.626-.494-.946-.727c-.218-.16-.465-.29-.676-.45a2.285 2.285 0 0 1-.691-2.75a1.51 1.51 0 0 1 1.069-.895c.904-.225 1.86-.1 2.677.35M8.07 11.867c0 .5-.416.92-.916.924c-.51 0-.946-.437-.931-.946a.955.955 0 0 1 .945-.91a.915.915 0 0 1 .902.932m8.802-.902c.509 0 .88.364.887.88a.933.933 0 0 1-.931.946a.933.933 0 0 1-.91-.931c0-.531.386-.902.947-.902z");
}

.x6t1a5bqg {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 19a7 7 0 1 0 0-14a7 7 0 0 0 0 14m0 1a8 8 0 1 0 0-16a8 8 0 0 0-8 8a8 8 0 0 0 8 8");
}

</style>
