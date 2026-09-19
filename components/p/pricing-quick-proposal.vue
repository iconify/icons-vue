<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e90cm3b1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e90cm3b1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:pricing-quick-proposal" /></template>
