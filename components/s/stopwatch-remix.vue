<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vye12zu8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vye12zu8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:stopwatch-remix" /></template>
