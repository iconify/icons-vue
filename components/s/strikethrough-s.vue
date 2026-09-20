<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbw78gb8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbw78gb8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:strikethrough-s" /></template>
