<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cm2bsui2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cm2bsui2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:trend-up" /></template>
