<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvz5ev-fh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvz5ev-fh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:rest-time-fill" /></template>
