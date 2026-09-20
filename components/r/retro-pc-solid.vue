<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwyn26gpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vwyn26gpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:retro-pc-solid" /></template>
