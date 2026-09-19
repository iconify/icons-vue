<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fe37jgblf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="fe37jgblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:text-underline" /></template>
