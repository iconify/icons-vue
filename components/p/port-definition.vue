<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7m4zg46k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e7m4zg46k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:port-definition" /></template>
