<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/duw237w5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="duw237w5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:space-bar-20" /></template>
