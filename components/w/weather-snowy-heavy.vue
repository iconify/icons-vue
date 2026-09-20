<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/huyz1cckc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="huyz1cckc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:weather-snowy-heavy" /></template>
