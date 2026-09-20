<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e84jpyb_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e84jpyb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:music-note-trebble-clef-remix" /></template>
