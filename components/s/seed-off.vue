<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6-l7qbsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6-l7qbsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:seed-off" /></template>
