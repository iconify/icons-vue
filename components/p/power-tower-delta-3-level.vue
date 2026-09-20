<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i46bncbwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i46bncbwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:power-tower-delta-3-level" /></template>
