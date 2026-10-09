<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i36jb0_kr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i36jb0_kr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:waterfall-48" /></template>
