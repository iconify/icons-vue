<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyw1c2bvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lyw1c2bvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:symbol-snippet" /></template>
