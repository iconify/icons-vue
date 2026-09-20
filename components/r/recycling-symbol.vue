<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ym-0ijbwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ym-0ijbwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:recycling-symbol" /></template>
