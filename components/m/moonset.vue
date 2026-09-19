<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rl05jy16c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rl05jy16c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:moonset" /></template>
