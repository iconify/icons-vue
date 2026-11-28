<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7_j0sbbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary u7_j0sbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:waveform-medium-duotone" /></template>
