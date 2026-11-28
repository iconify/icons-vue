<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rztp92rvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rztp92rvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:text-to-speech-solid" /></template>
