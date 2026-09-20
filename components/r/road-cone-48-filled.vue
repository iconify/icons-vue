<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v784fwb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:road-cone-48-filled" /></template>
<style>
.v784fwb4b {
  fill: currentColor;
  d: path("M22.388 4a2.5 2.5 0 0 0-2.43 1.91c-1.382 5.684-3.07 11.898-4.77 18.09H25.5a1.5 1.5 0 1 1 0 3H14.362l-1.099 4H27.5a1.5 1.5 0 0 1 0 3H12.445a654 654 0 0 0-1.865 7H5.5a1.5 1.5 0 0 0 0 3h37a1.5 1.5 0 1 0 0-3h-5.08L28.046 5.856A2.5 2.5 0 0 0 25.632 4z");
}

</style>
