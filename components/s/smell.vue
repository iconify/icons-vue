<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvkkn3b9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zvkkn3b9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:smell" /></template>
