<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0lownbvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0lownbvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:robot-vacuum-alert" /></template>
