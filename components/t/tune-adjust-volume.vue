<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v84t6sqao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v84t6sqao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:tune-adjust-volume" /></template>
