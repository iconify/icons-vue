<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6i5kabta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u6i5kabta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:power-tower-portal-2-level" /></template>
