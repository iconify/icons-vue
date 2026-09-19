<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1hqot9ea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1hqot9ea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:player-next-thin" /></template>
