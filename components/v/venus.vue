<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-qd56bzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1152,"height":1792};
const content = `<path class="e-qd56bzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:venus" /></template>
