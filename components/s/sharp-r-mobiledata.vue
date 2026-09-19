<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gbsgqotvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-r-mobiledata" /></template>
<style>
.gbsgqotvf {
  fill: currentColor;
  d: path("M7.8 7.2L9 10H7L5.87 7.33H4V10H2V2h7v5.2zM7 4H4v1.33h3z");
}

</style>
