<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv5badiir.css';
import '../../css/e/e5a3g-bwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zv5badiir"/><path class="e5a3g-bwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:warning-square-filled" /></template>
