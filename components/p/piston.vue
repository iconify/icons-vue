<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dutm75gbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dutm75gbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:piston" /></template>
