<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVG9Z178bDp"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="oewu8l5vb"/><path class="zwhljc64u"/></g></mask></defs><circle mask="url(#SVG9Z178bDp)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:water-drop-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.ft5dv1b6b {
  fill: none;
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.kvn14gsjy {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
}

.oewu8l5vb {
  d: path("M16.025 7.402c-.37-.19-.468-.44-.44-.713c.027-.252.162-.525.294-.791l.072-.146c.218-.45.365-.866-.123-1.11a14 14 0 0 0-1.705.295c-4.115.981-6.731 3.637-7.71 5.531a7.133 7.133 0 1 0 9.612-3.066m-2.416-.24c-2.945.988-4.763 2.955-5.418 4.224a5.133 5.133 0 1 0 6.916-2.207a2.87 2.87 0 0 1-1.121-1a2.6 2.6 0 0 1-.378-1.017");
}

.zwhljc64u {
  d: path("M10.458 13.183a1 1 0 0 0-1.965-.374l.982.191l-.982-.191v.002l-.001.003l-.001.006l-.003.017a3 3 0 0 0-.029.205a4 4 0 0 0-.023.506c.005.4.067.973.336 1.541c.269.566.667.975.97 1.231a4 4 0 0 0 .578.408l.015.009l.006.003l.003.001c.001.001.002.002.476-.88l-.474.881a1 1 0 0 0 .955-1.757l-.007-.004l-.053-.033a2 2 0 0 1-.209-.156a1.7 1.7 0 0 1-.452-.559a1.7 1.7 0 0 1-.144-.71a2 2 0 0 1 .02-.331z");
}

</style>
