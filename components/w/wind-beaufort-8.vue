<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azb25zw4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="azb25zw4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:wind-beaufort-8" /></template>
