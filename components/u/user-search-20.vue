<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sd353pbda.css';
import '../../css/a/ad6ngxjuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sd353pbda"/><path class="ad6ngxjuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:user-search-20" /></template>
