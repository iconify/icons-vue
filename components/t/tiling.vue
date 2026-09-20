<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/roy_foenl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="roy_foenl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:tiling" /></template>
