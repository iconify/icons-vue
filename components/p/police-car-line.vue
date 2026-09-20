<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mm_kv8bri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mm_kv8bri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:police-car-line" /></template>
