<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/teh_ozbsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="teh_ozbsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:puzzle-minus" /></template>
