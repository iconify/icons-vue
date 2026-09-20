<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9u975bns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="i9u975bns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:square-cap-solid" /></template>
