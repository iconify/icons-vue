<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hp49s6dbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hp49s6dbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:oil-temperature" /></template>
