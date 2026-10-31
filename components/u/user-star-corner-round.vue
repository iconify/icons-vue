<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpeeh0b8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vpeeh0b8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-star-corner-round" /></template>
