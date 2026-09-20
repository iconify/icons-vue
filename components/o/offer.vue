<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw9lk9bet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uw9lk9bet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:offer" /></template>
