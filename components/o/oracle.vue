<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbko2ebwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbko2ebwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:oracle" /></template>
