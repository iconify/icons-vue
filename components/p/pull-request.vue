<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_ocxnu1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d_ocxnu1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:pull-request" /></template>
