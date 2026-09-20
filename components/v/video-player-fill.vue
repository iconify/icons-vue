<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7eb2bcam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7eb2bcam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:video-player-fill" /></template>
