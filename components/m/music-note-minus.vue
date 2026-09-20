<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gr1hr6bkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gr1hr6bkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:music-note-minus" /></template>
