<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0_q8-y1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u0_q8-y1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:split-vertically" /></template>
