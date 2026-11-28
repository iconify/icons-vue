<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2o77lodb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2o77lodb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:stethoscope-check" /></template>
