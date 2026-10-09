<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqjo_17sw.css';
import '../../css/f/fv344tbkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bqjo_17sw"/><path class="fv344tbkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:micro-inverter-20-bold" /></template>
