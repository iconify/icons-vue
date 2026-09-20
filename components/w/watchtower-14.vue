<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f21xtmb7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="f21xtmb7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:watchtower-14" /></template>
