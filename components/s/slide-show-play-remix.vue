<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qllraju_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qllraju_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:slide-show-play-remix" /></template>
