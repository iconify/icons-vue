<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qc3492_1p.css';
import '../../css/b/bud9nuiqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qc3492_1p"/><path class="bud9nuiqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:promote" /></template>
