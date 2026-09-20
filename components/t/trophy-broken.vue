<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dc5q0zoak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dc5q0zoak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:trophy-broken" /></template>
