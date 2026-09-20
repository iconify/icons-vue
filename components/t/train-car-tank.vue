<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-ld3yycm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-ld3yycm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:train-car-tank" /></template>
