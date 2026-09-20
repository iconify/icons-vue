<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5nbrpbhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5nbrpbhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:voice-scan-1" /></template>
