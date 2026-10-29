<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ee4-h3bwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ee4-h3bwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:spray-can" /></template>
