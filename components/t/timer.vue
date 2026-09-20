<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jw8_6e7bf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jw8_6e7bf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:timer" /></template>
