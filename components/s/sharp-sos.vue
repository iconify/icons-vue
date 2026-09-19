<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvi4e81lb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-sos" /></template>
<style>
.bvi4e81lb {
  fill: currentColor;
  d: path("M15.5 7h-7v10h7zm-2 8h-3V9h3zM1 15h4v-2H1V7h6v2H3v2h4v6H1zm16 0h4v-2h-4V7h6v2h-4v2h4v6h-6z");
}

</style>
