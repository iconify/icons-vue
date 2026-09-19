<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqt70smsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="dqt70smsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:right-arrow-circled-filled" /></template>
