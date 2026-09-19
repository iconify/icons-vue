<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-wtuh18x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e-wtuh18x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:phone-off" /></template>
