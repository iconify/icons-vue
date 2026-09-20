<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dovmwm1tw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dovmwm1tw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:sumo-logic" /></template>
