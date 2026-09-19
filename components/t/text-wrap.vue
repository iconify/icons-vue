<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrzzp4k-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rrzzp4k-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:text-wrap" /></template>
