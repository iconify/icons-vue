<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4l6zw40o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4l6zw40o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:proximity-sensor" /></template>
