<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzih4kbct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzih4kbct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:tilt-window-closed" /></template>
