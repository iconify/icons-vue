<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iih1xib-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sd-outline-sharp" /></template>
<style>
.iih1xib-k {
  fill: currentColor;
  d: path("M3 19V5h18v14zm1-1h16V6H4zm2.616-3.308H11v-3.076H7.5v-1.424h2.616v.5H11V9.308H6.616v3.077h3.5v1.423H7.5v-.5h-.885zm6.384 0h3.789l.595-.615V9.904l-.596-.596H13zm.885-.884v-3.616H16.5v3.616zM4 18V6z");
}

</style>
