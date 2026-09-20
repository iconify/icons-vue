<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftnvldb1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ftnvldb1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:rhombus-medium" /></template>
