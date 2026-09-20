<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l36sqt1cl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l36sqt1cl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:sim-card-line" /></template>
