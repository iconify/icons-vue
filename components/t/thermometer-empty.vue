<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxyu0ybfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":512};
const content = `<path class="cxyu0ybfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:thermometer-empty" /></template>
