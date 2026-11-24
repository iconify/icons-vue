<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="esn7fzfag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:police-station-alt-fill" /></template>
<style>
.esn7fzfag {
  fill: currentColor;
  d: path("M20 20h1a1 1 0 0 1 0 2h-6v-3a3 3 0 1 0-6 0v3H3a1 1 0 0 1 0-2h1V5a3 3 0 0 1 3-3h10a3 3 0 0 1 3 3ZM9.75 5A1.75 1.75 0 0 0 8 6.75v1.875c.001 2.409 1.475 4.097 3.594 5.039a1 1 0 0 0 .812 0c2.119-.942 3.593-2.63 3.594-5.039V6.75A1.75 1.75 0 0 0 14.25 5ZM13 19v3h-2v-3a1 1 0 0 1 2 0");
}

</style>
