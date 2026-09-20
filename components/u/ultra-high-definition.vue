<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcv2l6t1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rcv2l6t1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:ultra-high-definition" /></template>
