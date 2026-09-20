<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhcb-1bog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhcb-1bog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:volume-vibrate" /></template>
