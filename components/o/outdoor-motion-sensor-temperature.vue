<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1oyd7blj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1oyd7blj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:outdoor-motion-sensor-temperature" /></template>
