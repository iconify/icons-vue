<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hflbk-bmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hflbk-bmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:map-pin-plus" /></template>
