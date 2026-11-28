<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2r3rbcew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2r3rbcew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:wrench-check" /></template>
