<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hppnk8b9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hppnk8b9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:treat-off" /></template>
