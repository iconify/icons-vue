<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw2r7sb3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":376,"height":432};
const content = `<path class="uw2r7sb3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:paypal" /></template>
