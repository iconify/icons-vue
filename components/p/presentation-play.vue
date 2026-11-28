<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubxw1crkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubxw1crkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:presentation-play" /></template>
