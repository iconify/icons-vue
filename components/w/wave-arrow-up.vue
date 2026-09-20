<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfptfslfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vfptfslfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wave-arrow-up" /></template>
