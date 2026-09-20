<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1y2nlbbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c1y2nlbbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:trademark-solid" /></template>
