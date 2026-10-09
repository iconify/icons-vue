<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2g-f1blp.css';
import '../../css/w/wut29u08z.css';
import '../../css/x/x1osh-brd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u2g-f1blp"/><path class="wut29u08z"/><path class="x1osh-brd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wine-glass-20" /></template>
