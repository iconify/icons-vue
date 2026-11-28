<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wokiifbgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wokiifbgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:shield-star" /></template>
