<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fl4di9mpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="fl4di9mpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:red-river" /></template>
