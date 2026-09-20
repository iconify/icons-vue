<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgorfdcox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mgorfdcox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:step-out-16" /></template>
