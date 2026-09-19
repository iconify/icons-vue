<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vie_4_2vx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vie_4_2vx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:rounded-mirror" /></template>
