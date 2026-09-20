<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2e0i2d_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2e0i2d_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:stopwatch-remove-outline" /></template>
