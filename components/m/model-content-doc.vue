<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6ajanxdn.css';
import '../../css/b/b1_a9z27d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f6ajanxdn"/><path class="b1_a9z27d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:model-content-doc" /></template>
