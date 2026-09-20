<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4s7-rm9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="o4s7-rm9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:moon-26" /></template>
