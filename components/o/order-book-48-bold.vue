<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4mctibtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q4mctibtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:order-book-48-bold" /></template>
