<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q86g-lw1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q86g-lw1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:media-record" /></template>
