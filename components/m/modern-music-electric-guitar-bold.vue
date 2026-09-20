<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eul60_acn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eul60_acn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:modern-music-electric-guitar-bold" /></template>
