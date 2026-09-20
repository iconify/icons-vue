<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0vvwhbno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v0vvwhbno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:xbox-controller-battery-warning" /></template>
