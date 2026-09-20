<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmt7afbzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="rmt7afbzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:metronome" /></template>
