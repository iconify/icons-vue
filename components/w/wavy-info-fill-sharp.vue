<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zstyur1bn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wavy-info-fill-sharp" /></template>
<style>
.zstyur1bn {
  fill: currentColor;
  d: path("M20.217 8.53c2.376 1.655 2.376 5.285 0 6.94c.617 2.786-1.961 5.364-4.747 4.747c-1.655 2.376-5.285 2.376-6.94 0c-2.786.617-5.364-1.961-4.747-4.747c-2.376-1.655-2.376-5.285 0-6.94c-.617-2.786 1.961-5.364 4.747-4.747c1.655-2.376 5.285-2.376 6.94 0c2.786-.617 5.364 1.961 4.747 4.747M12 7a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm1 4a1 1 0 0 0-2 0v4a1 1 0 0 0 2 0Z");
}

</style>
