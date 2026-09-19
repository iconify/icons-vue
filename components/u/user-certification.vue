<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byc7-gb-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="byc7-gb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:user-certification" /></template>
