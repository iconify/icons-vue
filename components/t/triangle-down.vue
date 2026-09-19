<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/up4_10tsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="up4_10tsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:triangle-down" /></template>
