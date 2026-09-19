<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k20av7rgb.css';
import '../../css/h/hzik1vb6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k20av7rgb"/><path class="hzik1vb6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:snow-density" /></template>
