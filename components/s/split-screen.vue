<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3xz9b9iu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o3xz9b9iu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:split-screen" /></template>
