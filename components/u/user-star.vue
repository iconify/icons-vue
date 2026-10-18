<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iy1842boi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iy1842boi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:user-star" /></template>
