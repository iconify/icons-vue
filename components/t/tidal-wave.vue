<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ct-i0ab8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ct-i0ab8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:tidal-wave" /></template>
