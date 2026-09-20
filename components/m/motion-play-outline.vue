<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzn4iv5xp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzn4iv5xp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:motion-play-outline" /></template>
