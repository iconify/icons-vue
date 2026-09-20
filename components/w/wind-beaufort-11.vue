<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sf5ad9bvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="sf5ad9bvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:wind-beaufort-11" /></template>
