<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frcqdgejz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="frcqdgejz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:power-socket" /></template>
