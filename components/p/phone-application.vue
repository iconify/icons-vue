<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kipqqwb5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kipqqwb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:phone-application" /></template>
