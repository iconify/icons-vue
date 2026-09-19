<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbz8j5yuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wbz8j5yuw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:trace" /></template>
