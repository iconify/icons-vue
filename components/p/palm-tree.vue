<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzt0k9bvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nzt0k9bvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:palm-tree" /></template>
