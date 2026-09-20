<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmpfof1_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmpfof1_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:train-car-box-open" /></template>
