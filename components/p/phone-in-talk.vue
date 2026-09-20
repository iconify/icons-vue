<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wh85sebgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wh85sebgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:phone-in-talk" /></template>
