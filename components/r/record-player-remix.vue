<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmo-e-bly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fmo-e-bly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:record-player-remix" /></template>
