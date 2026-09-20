<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxs2libfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="uxs2libfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:owm-day-741" /></template>
