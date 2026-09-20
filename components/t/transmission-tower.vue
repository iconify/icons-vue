<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2wxst5fg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2wxst5fg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:transmission-tower" /></template>
