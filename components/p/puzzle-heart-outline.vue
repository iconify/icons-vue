<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g32c3xbmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g32c3xbmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:puzzle-heart-outline" /></template>
