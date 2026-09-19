<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/boof0ab7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="boof0ab7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:pentagon-outline" /></template>
