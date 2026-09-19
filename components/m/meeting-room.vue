<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tq-ey0bqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tq-ey0bqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:meeting-room" /></template>
