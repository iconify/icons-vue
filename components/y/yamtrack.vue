<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9oa8dbac.css';
import '../../css/g/gc5xy5own.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<ellipse class="f9oa8dbac"/><path class="gc5xy5own"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yamtrack" /></template>
