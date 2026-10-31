<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9bdq4btr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9bdq4btr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:waveform-bulk-round" /></template>
