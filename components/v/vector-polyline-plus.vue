<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y91yaib5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y91yaib5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:vector-polyline-plus" /></template>
