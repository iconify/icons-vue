<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skwzy5p_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="skwzy5p_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:previous" /></template>
