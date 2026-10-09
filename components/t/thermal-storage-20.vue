<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjfogtdwu.css';
import '../../css/s/s315aabjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vjfogtdwu"/><path class="s315aabjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:thermal-storage-20" /></template>
