<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8d70voog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8d70voog primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:waveform-low-duotone" /></template>
