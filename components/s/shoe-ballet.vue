<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgf-7tbau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgf-7tbau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shoe-ballet" /></template>
