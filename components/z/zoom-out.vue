<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwvsdd0eg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gwvsdd0eg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:zoom-out" /></template>
