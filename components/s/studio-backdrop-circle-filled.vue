<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGUzwpcdin"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="yo4uvc_5a"/><path class="npa-dd1fh"/></g></mask></defs><circle mask="url(#SVGUzwpcdin)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:studio-backdrop-circle-filled" /></template>
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

.npa-dd1fh {
  d: path("M4.75 5.5a1 1 0 0 1 1-1h14.5a1 1 0 1 1 0 2H5.75a1 1 0 0 1-1-1m1.97 14l1.26-6.304l-1.96-.392l-1.381 6.902a1.5 1.5 0 0 0 1.47 1.794H19.89a1.5 1.5 0 0 0 1.471-1.794l-1.38-6.902l-1.962.392L19.28 19.5z");
}

.yo4uvc_5a {
  d: path("M6 6a1.5 1.5 0 0 1 1.5-1.5h11A1.5 1.5 0 0 1 20 6v7a1.5 1.5 0 0 1-1.5 1.5h-11A1.5 1.5 0 0 1 6 13zm2 .5v6h10v-6z");
}

</style>
