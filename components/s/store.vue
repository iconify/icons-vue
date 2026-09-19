<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drlbf6fns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="drlbf6fns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:store" /></template>
