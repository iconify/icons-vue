<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh7ovfb-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rh7ovfb-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:music-pause" /></template>
