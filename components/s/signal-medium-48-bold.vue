<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cd-5y7buj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cd-5y7buj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:signal-medium-48-bold" /></template>
