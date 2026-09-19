<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vhomknb6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vhomknb6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:pivot-horizontal" /></template>
