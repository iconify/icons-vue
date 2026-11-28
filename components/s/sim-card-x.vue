<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2r2qnbzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o2r2qnbzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:sim-card-x" /></template>
