<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o_dd12x7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:thumbs-up-down-sharp" /></template>
<style>
.o_dd12x7r {
  fill: currentColor;
  d: path("M.5 13.27V5.4L5.4.5l.706.706l-.921 4.063H11.5v2.037l-2.59 5.963zM18.6 23.5l-.706-.706l.922-4.063H12.5v-2.037l2.59-5.963h8.41V18.6z");
}

</style>
