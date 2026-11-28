<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxs1s4jzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxs1s4jzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:sim-card" /></template>
