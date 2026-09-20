<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afriunohi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sports-kabaddi-sharp" /></template>
<style>
.afriunohi {
  fill: currentColor;
  d: path("M1.329 21.308L.62 20.6l3.535-3.534l-1.544-4.106l4.013-4.014q.223-.223.477-.334t.583-.112t.582.112t.477.334l2.039 1.95q.694.675 1.611 1.072q.918.398 1.985.494v1q-1.25-.096-2.358-.562q-1.107-.465-1.846-1.184l-1.046-1.008l-3.042 3.042l2.292 2.342V21.5h-1v-4.98l-2.3-2.124v3.162zm14.05.192v-6.27l2.177-2.076l-.908-4.808q-.76.931-1.594 1.675t-1.898 1.063q-.364-.05-.717-.205q-.353-.156-.622-.406q1.164-.18 2.238-.964t1.586-1.64l.961-1.6q.329-.54.896-.7q.568-.161 1.139.081l4.742 1.996V11.5h-1V8.292l-2.954-1.2L22.264 21.5h-1.1l-1.858-7.827l-2.927 2.25V21.5zM9.678 8.278q-.492-.492-.492-1.201t.492-1.201t1.2-.492t1.202.492t.491 1.201t-.491 1.201t-1.201.491t-1.201-.491m5.846-4.077q-.491-.492-.491-1.201t.491-1.201t1.201-.491t1.201.491q.491.492.491 1.201t-.491 1.201q-.491.491-1.201.491t-1.201-.491");
}

</style>
