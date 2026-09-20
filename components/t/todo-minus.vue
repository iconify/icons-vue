<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/divcj272b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="divcj272b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:todo-minus" /></template>
