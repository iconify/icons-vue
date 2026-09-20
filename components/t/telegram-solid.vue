<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-i500dqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-i500dqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:telegram-solid" /></template>
