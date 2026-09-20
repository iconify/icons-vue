<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqdbfbchb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fqdbfbchb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:right-up-corner-arrow-1" /></template>
