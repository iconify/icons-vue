<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfr8jsk1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vfr8jsk1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:subclassification" /></template>
