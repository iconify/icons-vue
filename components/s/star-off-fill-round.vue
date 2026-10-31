<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-tdchb9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-tdchb9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:star-off-fill-round" /></template>
