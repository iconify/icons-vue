<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uo6pqdbiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uo6pqdbiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:synology-dsm" /></template>
