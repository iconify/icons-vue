<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_rzrek6p.css';
import '../../css/v/vqp7s7b9z.css';
import '../../css/r/rbecf_bsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x_rzrek6p"/><path class="vqp7s7b9z"/><path class="rbecf_bsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wind-direction-20" /></template>
