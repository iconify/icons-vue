<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGSD5DLcWh"><path class="k5-vjlrin"/><path clip-rule="evenodd" class="ahx8dr2ld"/></mask></defs><circle mask="url(#SVGSD5DLcWh)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:thumbs-down-circle-filled" /></template>
<style>
.ahx8dr2ld {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("M19.81 15.108a1 1 0 0 0 1-1v-5.5a1 1 0 0 0-1-1h-2.5a1 1 0 0 0-1 1v5.5a1 1 0 0 0 1 1zm-1.25-6a1 1 0 1 0 0 2a1 1 0 0 0 0-2m-6.73 9.335c.086.086.23.053.273-.056l.194-1.165a5.16 5.16 0 0 1 1.783-3.114v-4.68l-4.196-.84l-.076-.018a1.43 1.43 0 0 0-1.61.628l-.217.353l-.506 1.338a3.9 3.9 0 0 0 .018 2.809l.31.62c.242.483.733.788 1.272.79h1.505q.064 0 .124.007A1 1 0 0 1 11.8 16.35l-.148.594a2 2 0 0 0-.058.548l.014.41a.85.85 0 0 0 .202.521zm3.428-10.82l-4.948-.99A3.43 3.43 0 0 0 6.495 8.15l-.255.415a1 1 0 0 0-.102.206l-.534 1.41a5.9 5.9 0 0 0 .045 4.292q.015.041.037.082l.329.658a3.43 3.43 0 0 0 3.065 1.895h.525q-.018.225-.01.452l.014.41a2.85 2.85 0 0 0 .764 1.845l.042.042c1.191 1.191 3.227.628 3.635-1.007l.016-.078l.204-1.222a3.16 3.16 0 0 1 1.354-2.103a1 1 0 0 0 .456-.84v-5.98a1 1 0 0 0-.822-1.003");
}

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

</style>
