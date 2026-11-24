<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_z24obcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:police-station-alt-fill-round" /></template>
<style>
.e_z24obcs {
  fill: currentColor;
  d: path("M15 22v-3a3 3 0 1 0-6 0v3H3a1 1 0 0 1 0-2h1V7a5 5 0 0 1 5-5h6a5 5 0 0 1 5 5v13h1a1 1 0 0 1 0 2ZM10.5 5A2.5 2.5 0 0 0 8 7.5v1.125c.001 2.409 1.475 4.097 3.594 5.039a1 1 0 0 0 .812 0c2.119-.942 3.593-2.63 3.594-5.039V7.5A2.5 2.5 0 0 0 13.5 5ZM13 19v3h-2v-3a1 1 0 0 1 2 0");
}

</style>
