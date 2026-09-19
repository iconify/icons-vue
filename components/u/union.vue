<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhi88lb2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mhi88lb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:union" /></template>
