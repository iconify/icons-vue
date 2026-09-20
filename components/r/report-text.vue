<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jp9lhj91o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jp9lhj91o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:report-text" /></template>
