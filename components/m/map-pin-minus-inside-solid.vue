<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n04d5sb5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n04d5sb5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:map-pin-minus-inside-solid" /></template>
