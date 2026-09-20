<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uy2wy_b7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uy2wy_b7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:rfid-line" /></template>
