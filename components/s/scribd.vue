<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7itk7bvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1472,"height":1792};
const content = `<path class="s7itk7bvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:scribd" /></template>
