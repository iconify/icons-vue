<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hc2ypxcmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hc2ypxcmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:vis-gauge" /></template>
