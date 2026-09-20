<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pd0hb1b-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="pd0hb1b-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:railway-station-14" /></template>
