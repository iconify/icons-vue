<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2g7e0bth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:step-outline-sharp" /></template>
<style>
.z2g7e0bth {
  fill: currentColor;
  d: path("M19 15q-1.275 0-2.137-.862T16 12t.863-2.137T19 9t2.138.863T22 12t-.862 2.138T19 15M9 17l-1.4-1.425L10.175 13H2v-2h8.175L7.6 8.4L9 7l5 5z");
}

</style>
