<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gh0-fjbav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gh0-fjbav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:stratus" /></template>
