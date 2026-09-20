<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mi3saibgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="mi3saibgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:sthethoscope" /></template>
