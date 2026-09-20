<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGcysCaeMk"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="bsjipbkaq"/><path class="tfr8xz27w"/><path class="mgf5k7y8b"/></g></mask></defs><circle mask="url(#SVGcysCaeMk)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:photo-studio-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.bsjipbkaq {
  d: path("M3.9 5.5A1.5 1.5 0 0 1 5.4 4h6.2a1.5 1.5 0 0 1 1.5 1.5v3.8a1.5 1.5 0 0 1-1.5 1.5H5.4a1.5 1.5 0 0 1-1.5-1.5zm2 .5v2.8h5.2V6z");
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

.mgf5k7y8b {
  d: path("M19.75 11.706a1 1 0 0 0-1 1v7.059a1 1 0 1 0 2 0v-7.06a1 1 0 0 0-1-1");
}

.tfr8xz27w {
  d: path("M3.15 5a1 1 0 0 1 1-1h8.7a1 1 0 1 1 0 2h-8.7a1 1 0 0 1-1-1m2.07 8l.66-3.304l-1.96-.392l-.781 3.902A1.5 1.5 0 0 0 4.609 15h7.781a1.5 1.5 0 0 0 1.471-1.794l-.78-3.902l-1.962.392L11.78 13zm17.03 7a1 1 0 0 0-1-1h-3a1 1 0 1 0 0 2h3a1 1 0 0 0 1-1m-4.953-9c.313.166.73.421 1.058.731c.384.363.395.553.395.563s-.01.2-.395.563c-.328.31-.745.566-1.058.731h-.547V11zm.81 4.42a1.66 1.66 0 0 1-.753.168h-.604a2 2 0 0 1-2-2V11a2 2 0 0 1 2-2h.604c.262 0 .52.05.754.168c.795.402 2.642 1.51 2.642 3.126s-1.847 2.724-2.642 3.126");
}

</style>
