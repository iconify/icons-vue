<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y57omyb4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y57omyb4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:script-reference" /></template>
