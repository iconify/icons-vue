<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slqipu8ji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="slqipu8ji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:text-wrap-truncation" /></template>
