<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzr0lxblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xzr0lxblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:switch-layer-3" /></template>
