<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgz03y5cu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mgz03y5cu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:volume-off-outline" /></template>
