<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ruxgsbgmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ruxgsbgmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:map-pin-house-fill" /></template>
