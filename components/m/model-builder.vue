<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_kynueps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x_kynueps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:model-builder" /></template>
