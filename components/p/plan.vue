<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smumombga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="smumombga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:plan" /></template>
