<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrz9qccwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mrz9qccwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:scan-20" /></template>
