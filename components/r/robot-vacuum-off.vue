<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h45mtet1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h45mtet1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:robot-vacuum-off" /></template>
