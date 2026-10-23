<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsbdr7opj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rsbdr7opj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:thermometer-snowflake" /></template>
