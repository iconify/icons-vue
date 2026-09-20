<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o336t47vq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o336t47vq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tray-plus" /></template>
