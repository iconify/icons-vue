<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="k6z0vxb3b"/><path class="muzwturgd"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:solflare-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k6z0vxb3b {
  fill: var(--svg-color--ffef46, #ffef46);
  d: path("M24 0H0v24h24z");
}

.muzwturgd {
  fill: var(--svg-color--02050a, #02050a);
  d: path("m12.056 12.636l1.098-1.066l2.047.673c1.34.449 2.01 1.271 2.01 2.43c0 .878-.335 1.458-1.005 2.205l-.205.225l.075-.524c.297-1.906-.26-2.729-2.103-3.327zM9.3 6.112l5.584 1.87l-1.21 1.158l-2.903-.972c-1.005-.336-1.34-.878-1.47-2.018zm-.335 9.496l1.266-1.216l2.382.786c1.247.41 1.675.953 1.545 2.317zm-1.6-5.421c0-.355.186-.692.502-.972c.335.486.912.916 1.824 1.215l1.973.654l-1.098 1.066l-1.935-.636c-.894-.299-1.266-.748-1.266-1.327M13.21 20c4.094-2.729 6.29-4.58 6.29-6.86c0-1.514-.893-2.355-2.866-3.01l-1.489-.504l4.076-3.925l-.819-.879l-1.21 1.066L11.48 4c-1.768.58-4.001 2.28-4.001 3.981c0 .187.018.374.074.58c-1.47.84-2.066 1.626-2.066 2.598c0 .916.484 1.832 2.029 2.336l1.228.412L4.5 18l.819.878l1.321-1.214z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
