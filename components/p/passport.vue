<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft134lggm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ft134lggm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:passport" /></template>
