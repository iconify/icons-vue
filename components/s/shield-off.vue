<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oiwg1abwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oiwg1abwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:shield-off" /></template>
