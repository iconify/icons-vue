<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/us2ogcqly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="us2ogcqly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:star-minus" /></template>
