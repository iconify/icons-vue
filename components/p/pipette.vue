<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7zxa8g-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7zxa8g-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:pipette" /></template>
