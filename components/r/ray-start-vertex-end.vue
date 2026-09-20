<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdc383b_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdc383b_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:ray-start-vertex-end" /></template>
