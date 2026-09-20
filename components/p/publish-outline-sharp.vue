<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="usox12bez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:publish-outline-sharp" /></template>
<style>
.usox12bez {
  fill: currentColor;
  d: path("M11.5 19v-8.65l-2.33 2.33l-.708-.718L12 8.423l3.539 3.539l-.708.719L12.5 10.35V19zM5 9.039V5h14v4.039h-1V6H6v3.039z");
}

</style>
