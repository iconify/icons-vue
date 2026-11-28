<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcuhlcb9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vcuhlcb9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:tv-play" /></template>
