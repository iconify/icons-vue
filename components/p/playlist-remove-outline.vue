<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hut2hdf3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:playlist-remove-outline" /></template>
<style>
.hut2hdf3b {
  fill: currentColor;
  d: path("m14.496 21.308l-.708-.708l2.6-2.6l-2.6-2.6l.708-.708l2.6 2.6l2.6-2.6l.708.708l-2.6 2.6l2.6 2.6l-.708.708l-2.6-2.6zM3.596 15.5v-1h7v1zm0-4v-1h11v1zm0-4v-1h11v1z");
}

</style>
