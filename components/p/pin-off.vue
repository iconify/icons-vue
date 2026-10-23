<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yd4b8lu0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yd4b8lu0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:pin-off" /></template>
