<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0kuq6b3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d0kuq6b3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:template" /></template>
