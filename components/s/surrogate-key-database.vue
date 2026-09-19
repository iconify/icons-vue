<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfjyxob3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xfjyxob3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:surrogate-key-database" /></template>
