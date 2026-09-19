<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9ac3eeei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l9ac3eeei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:summary-kpi" /></template>
