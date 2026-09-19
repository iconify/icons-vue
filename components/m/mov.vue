<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ch6k2lb3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ch6k2lb3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:mov" /></template>
