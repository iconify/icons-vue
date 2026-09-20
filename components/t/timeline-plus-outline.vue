<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4q2c_9ec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4q2c_9ec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:timeline-plus-outline" /></template>
