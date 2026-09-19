<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt8j62bgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mt8j62bgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:spiral" /></template>
