<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4ge2mb4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v4ge2mb4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:twitter" /></template>
