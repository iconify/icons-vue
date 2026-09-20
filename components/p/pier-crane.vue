<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4au4iqiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g4au4iqiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pier-crane" /></template>
