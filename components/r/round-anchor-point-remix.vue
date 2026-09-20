<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ff-478dna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ff-478dna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:round-anchor-point-remix" /></template>
