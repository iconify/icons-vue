<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s36yjubhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s36yjubhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:snow" /></template>
