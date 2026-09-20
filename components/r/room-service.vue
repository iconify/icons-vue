<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_z8_tzny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_z8_tzny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:room-service" /></template>
