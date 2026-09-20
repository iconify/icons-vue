<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2_c2vsll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="g2_c2vsll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:recording-tape-bubble-circle-solid" /></template>
