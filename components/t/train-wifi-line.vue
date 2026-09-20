<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7rcmwb4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a7rcmwb4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:train-wifi-line" /></template>
