<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="bpbxngsox"/><path clip-rule="evenodd" class="a6hzkqzrt"/><path class="vhpt9acsp"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:oni-background" /></template>
<style>
.a6hzkqzrt {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12.002 14.51a2.5 2.5 0 1 0 0-5a2.5 2.5 0 0 0 0 5m0 1.999a4.498 4.498 0 1 0 0-8.996a4.498 4.498 0 0 0 0 8.996");
}

.bpbxngsox {
  fill: var(--svg-color--43adb2, #43adb2);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.vhpt9acsp {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.4 18.833c-.11-.48-.55-.8-1.04-.854a6.11 6.11 0 0 1-5.323-4.98c-.09-.55-.535-1-1.09-1c-.55 0-1.01.45-.94 1a8.15 8.15 0 0 0 7.474 7c.624.04 1.06-.556.92-1.166m6.434-6.273c.6.14 1.195-.285 1.165-.9A8.224 8.224 0 0 0 12.41 4c-.525-.03-.935.41-.935.935c0 .58.5 1.025 1.08 1.09c2.815.3 5.164 2.64 5.424 5.474c.045.5.37.95.855 1.06");
}

</style>
