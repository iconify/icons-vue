<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vp7d-bcfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vp7d-bcfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:politics-speech-solid" /></template>
