<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-50j0_4f.css';
import '../../css/u/uj3418bvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u-50j0_4f"/><path class="uj3418bvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:task-remove" /></template>
