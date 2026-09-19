<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snjs1fb4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-water-drop" /></template>
<style>
.snjs1fb4z {
  fill: currentColor;
  d: path("M12 2c-5.33 4.55-8 8.48-8 11.8c0 4.98 3.8 8.2 8 8.2s8-3.22 8-8.2c0-3.32-2.67-7.25-8-11.8m1 16.91c-.32.06-.65.09-1 .09c-2.69 0-4.88-1.94-5-5h1.5c.08 2.07 1.5 3.5 3.5 3.5c.35 0 .69-.04 1-.13z");
}

</style>
