<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yg-gktmdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yg-gktmdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:save-outline" /></template>
