<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e28ifp_ws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e28ifp_ws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:time-5" /></template>
