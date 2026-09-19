<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6de9d63f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r6de9d63f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:stamp" /></template>
