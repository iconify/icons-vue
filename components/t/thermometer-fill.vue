<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mirf0bblj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mirf0bblj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:thermometer-fill" /></template>
