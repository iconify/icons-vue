<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7-0lx72p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v7-0lx72p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:text-long-paragraph" /></template>
