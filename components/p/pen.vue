<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8dfpftnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e8dfpftnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:pen" /></template>
