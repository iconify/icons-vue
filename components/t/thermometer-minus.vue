<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1fhrefdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n1fhrefdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:thermometer-minus" /></template>
