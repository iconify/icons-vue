<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/um5-vnbtu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="um5-vnbtu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:nut-off" /></template>
