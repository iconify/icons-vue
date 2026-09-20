<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhkb8obdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhkb8obdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:microchip-solid" /></template>
