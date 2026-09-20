<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hq_av1bfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hq_av1bfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:snooze-clock-solid" /></template>
