<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy4rdnbav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gy4rdnbav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:razor-double-edge" /></template>
