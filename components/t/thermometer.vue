<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-6--gb1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="t-6--gb1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:thermometer" /></template>
