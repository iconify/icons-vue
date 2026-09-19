<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p41rr2x8b.css';
import '../../css/e/e00g5nbxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p41rr2x8b"/><path class="e00g5nbxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:page-number" /></template>
