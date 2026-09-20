<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhticabff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhticabff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:power-generator" /></template>
