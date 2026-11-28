<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqm4dwb3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqm4dwb3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:presentation-play" /></template>
