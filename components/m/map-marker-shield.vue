<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsi7l1byg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hsi7l1byg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:map-marker-shield" /></template>
