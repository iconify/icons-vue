<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifhpgcbyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifhpgcbyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:train-car-intermodal" /></template>
