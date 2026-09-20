<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsku83b7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hsku83b7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:solar-power" /></template>
