<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rel4yrbuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rel4yrbuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:report-linechart" /></template>
