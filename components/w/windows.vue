<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inzkwub1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="inzkwub1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:windows" /></template>
