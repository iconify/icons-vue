<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry4jo_b0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ry4jo_b0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sim" /></template>
