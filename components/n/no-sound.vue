<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhtpzrekm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:no-sound" /></template>
<style>
.mhtpzrekm {
  fill: currentColor;
  d: path("m14.785 15.308l-.708-.708l2.6-2.6l-2.6-2.6l.708-.708l2.6 2.6l2.6-2.6l.707.708l-2.6 2.6l2.6 2.6l-.707.708l-2.6-2.6zM4.308 14v-4H7.73l3.577-3.577v11.154L7.73 14z");
}

</style>
