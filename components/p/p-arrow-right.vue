<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltsx_kb3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ltsx_kb3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:p-arrow-right" /></template>
