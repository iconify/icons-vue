<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d45cpc0pf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d45cpc0pf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-windows-light" /></template>
