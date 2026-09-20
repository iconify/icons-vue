<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0aegk_3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r0aegk_3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:movie-plus" /></template>
