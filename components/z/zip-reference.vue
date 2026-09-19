<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ty41ygy9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ty41ygy9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:zip-reference" /></template>
