<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eplpgs1zp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eplpgs1zp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:microphone-question-outline" /></template>
