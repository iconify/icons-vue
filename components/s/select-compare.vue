<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rn_8x9o0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rn_8x9o0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:select-compare" /></template>
