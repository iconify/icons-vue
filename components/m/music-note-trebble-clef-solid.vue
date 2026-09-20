<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwyk05bnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wwyk05bnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:music-note-trebble-clef-solid" /></template>
