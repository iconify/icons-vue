<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvx1lebqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-equalizer" /></template>
<style>
.tvx1lebqh {
  fill: currentColor;
  d: path("M16 9h4v11h-4zm-6-5h4v16h-4zm-6 8h4v8H4z");
}

</style>
