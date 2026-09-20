<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/duxijwb8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duxijwb8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pan-top-right" /></template>
