<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wr9yu5bwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wr9yu5bwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tribal-shield" /></template>
