<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yy8bvsbha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yy8bvsbha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:sogou" /></template>
