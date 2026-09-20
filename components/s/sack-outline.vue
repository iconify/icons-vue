<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njpmz0b0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="njpmz0b0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sack-outline" /></template>
