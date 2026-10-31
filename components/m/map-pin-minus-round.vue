<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w99-s6t3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w99-s6t3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:map-pin-minus-round" /></template>
