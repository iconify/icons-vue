<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0-u15bnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m0-u15bnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:parachute-outline" /></template>
