<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcruj4cal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vcruj4cal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:multiplier-1-5x" /></template>
