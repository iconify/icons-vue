<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4ma5v20c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="w4ma5v20c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:wind-beaufort-6" /></template>
