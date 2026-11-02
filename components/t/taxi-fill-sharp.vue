<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nt3uymyok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:taxi-fill-sharp" /></template>
<style>
.nt3uymyok {
  fill: currentColor;
  d: path("M14 4a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2ZM3 11h.382l1.724-3.447A1 1 0 0 1 6 7h12c.379 0 .725.214.894.553L20.618 11H21a1 1 0 0 1 0 2v5a1 1 0 0 1-1 1h-1v1a1 1 0 0 1-1 1h-2a1 1 0 0 1-1-1v-1H9v1a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1v-1H4a1 1 0 0 1-1-1v-5a1 1 0 0 1 0-2m15.382 0l-1-2H6.618l-1 2ZM8 14a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm8.01 0H16a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
