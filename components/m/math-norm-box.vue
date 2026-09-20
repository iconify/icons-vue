<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp2qudbik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xp2qudbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:math-norm-box" /></template>
