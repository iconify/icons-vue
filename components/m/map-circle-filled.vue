<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGExllwbCd"><path class="k5-vjlrin"/><g class="ivjvz2eii"><path clip-rule="evenodd" class="pwtppyf3q"/><path clip-rule="evenodd" class="hmhqlibuc"/><path class="k6xam812o"/></g></mask></defs><circle mask="url(#SVGExllwbCd)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:map-circle-filled" /></template>
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

.hmhqlibuc {
  fill-rule: evenodd;
  d: path("M8 10.286C8 13.199 10.805 18 13 18s5-4.801 5-7.714C18 7.38 15.777 5 13 5s-5 2.381-5 5.286m8 0C16 12.24 13.803 16 13 16s-3-3.76-3-5.714C10 8.456 11.36 7 13 7s3 1.456 3 3.286");
}

.ivjvz2eii {
  fill: var(--svg-color--000, #000);
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.k6xam812o {
  d: path("M16.73 13a1 1 0 1 1 0-2a3 3 0 0 1 2.89 2.197l1.39 5A3 3 0 0 1 18.118 22H7.88a3 3 0 0 1-2.89-3.803l1.389-5A3 3 0 0 1 9.27 11a1 1 0 0 1 0 2a1 1 0 0 0-.963.732l-1.39 5A1 1 0 0 0 7.882 20H18.12a1 1 0 0 0 .963-1.268l-1.389-5A1 1 0 0 0 16.73 13");
}

.pwtppyf3q {
  fill-rule: evenodd;
  d: path("M13 13a2.5 2.5 0 1 0 0-5a2.5 2.5 0 0 0 0 5m0-3a.5.5 0 1 1 0 1a.5.5 0 0 1 0-1");
}

</style>
