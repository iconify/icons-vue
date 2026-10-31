<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qi1d2ebjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qi1d2ebjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:waveform-duotone-round" /></template>
