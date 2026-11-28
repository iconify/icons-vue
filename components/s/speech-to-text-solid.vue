<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugr2cuw1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugr2cuw1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:speech-to-text-solid" /></template>
