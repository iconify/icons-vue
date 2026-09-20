<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9ljbbcsg.css';
import '../../css/m/mhbz-4bgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m9ljbbcsg"/><path class="mhbz-4bgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:map-distance-filled" /></template>
