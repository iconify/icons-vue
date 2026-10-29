<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/io_avja3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="io_avja3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:parentheses" /></template>
