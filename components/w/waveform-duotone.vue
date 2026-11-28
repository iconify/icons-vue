<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb2b7xbau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary wb2b7xbau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:waveform-duotone" /></template>
