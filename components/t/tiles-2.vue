<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnfpi3hic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="qnfpi3hic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:tiles-2" /></template>
