<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5v661b1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i5v661b1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:skip-back-20-bold" /></template>
