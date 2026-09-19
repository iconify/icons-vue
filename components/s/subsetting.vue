<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rium4wb9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rium4wb9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:subsetting" /></template>
