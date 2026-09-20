<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u45bgcbrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u45bgcbrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:teknikkdeler-light" /></template>
