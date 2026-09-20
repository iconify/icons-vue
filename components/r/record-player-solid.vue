<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7n3b9bth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e7n3b9bth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:record-player-solid" /></template>
