<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/foca7bcey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="foca7bcey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:ws-selector" /></template>
