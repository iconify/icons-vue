<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8gkcej6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p8gkcej6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:port-usage" /></template>
