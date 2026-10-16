<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eg_2veb3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eg_2veb3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:moonrise-48-bold" /></template>
