<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="om_wtsb_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:view-compact" /></template>
<style>
.om_wtsb_y {
  fill: currentColor;
  d: path("M21.039 18.904V5.096zM2.961 9.173V5.096H6.98v4.077zm4.788 0V5.096h3.866v4.077zm4.635 0V5.096h3.865v4.077zm4.634 0V5.096h4.02v4.077zm0 4.885V9.942h4.02v4.116zm-4.634 0V9.942h3.865v4.116zm-4.635 0V9.942h3.866v4.116zm-4.789 0V9.942h4.02v4.116zm14.058 4.846v-4.077h4.02v4.077zm-4.634 0v-4.077h3.865v4.077zm-4.635 0v-4.077h3.866v4.077zm-4.789 0v-4.077h4.02v4.077z");
}

</style>
