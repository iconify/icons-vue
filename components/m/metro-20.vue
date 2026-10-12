<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlyagw35s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dlyagw35s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:metro-20" /></template>
