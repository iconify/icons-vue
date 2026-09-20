<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q234p0z5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q234p0z5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:music-rest-quarter" /></template>
