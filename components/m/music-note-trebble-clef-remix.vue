<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmjjd_bwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="vmjjd_bwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:music-note-trebble-clef-remix" /></template>
