<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qs37fsenr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qs37fsenr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:xing" /></template>
