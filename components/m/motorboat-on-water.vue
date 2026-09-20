<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqlmd9qxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zqlmd9qxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:motorboat-on-water" /></template>
