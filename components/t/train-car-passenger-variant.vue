<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_v0kzl5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_v0kzl5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:train-car-passenger-variant" /></template>
