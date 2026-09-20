<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crh91xb0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crh91xb0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:weather-sun" /></template>
