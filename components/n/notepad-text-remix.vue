<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fc6cptv2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fc6cptv2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:notepad-text-remix" /></template>
