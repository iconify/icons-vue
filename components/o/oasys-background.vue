<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="f0u-pjwzp"/><path class="abaqtsb1r"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:oasys-background" /></template>
<style>
.abaqtsb1r {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.314 14.112q.433-.474.77-1.043q.812-1.38.813-3.029c0-1.1-.269-2.129-.807-3.05a6 6 0 0 0-2.166-2.19A5.7 5.7 0 0 0 11.98 4a5.8 5.8 0 0 0-2.966.801a6.06 6.06 0 0 0-2.183 2.182a5.8 5.8 0 0 0-.813 3.015c0 1.09.272 2.157.813 3.082q.347.591.794 1.074C6.619 14.775 6 15.611 6 16.527C6 18.442 8.69 20 12 20s6-1.558 6-3.473c0-.936-.644-1.788-1.69-2.412zm-8.616 3.9c-.597-.45-.921-.965-.921-1.488c0-.644.493-1.279 1.387-1.79q.024-.015.052-.029q.37.303.788.551l.086.048c-.96.478-1.57 1.19-1.57 1.98q.001.379.178.728m4.307 1.097c-1.361 0-2.105-.6-2.105-.909s.744-.908 2.105-.908c1.362 0 2.106.599 2.106.908s-.744.909-2.106.909m2.858-.703a1 1 0 0 0 .022-.206c0-.933-1.293-1.69-2.88-1.69s-2.879.76-2.879 1.69q.001.105.022.206c-.527-.318-.854-.712-.854-1.122c0-.619.74-1.198 1.786-1.533q.877.299 1.829.298q1.02 0 1.947-.32c1.087.329 1.861.925 1.861 1.555c0 .41-.327.804-.854 1.122m1.45-.394q.177-.347.178-.728c0-.81-.638-1.533-1.634-2.014l.042-.022a6 6 0 0 0 .83-.58l.118.065c.894.512 1.387 1.147 1.387 1.791c0 .52-.321 1.038-.92 1.488");
}

.f0u-pjwzp {
  fill: var(--svg-color--00a84f, #00a84f);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
