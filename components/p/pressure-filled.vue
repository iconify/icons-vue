<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jv0lhnksd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jv0lhnksd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:pressure-filled" /></template>
