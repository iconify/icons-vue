<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1cik42pi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g1cik42pi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:text-italic" /></template>
