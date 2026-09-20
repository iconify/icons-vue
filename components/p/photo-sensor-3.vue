<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_y1_nl1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_y1_nl1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:photo-sensor-3" /></template>
