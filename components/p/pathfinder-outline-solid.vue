<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vv42esbjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vv42esbjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:pathfinder-outline-solid" /></template>
