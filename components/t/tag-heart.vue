<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcm41yf7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcm41yf7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tag-heart" /></template>
