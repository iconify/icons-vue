<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hy6ofvbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hy6ofvbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:square-play-solid" /></template>
