<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zs7_t6bwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="zs7_t6bwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:shield-compact" /></template>
