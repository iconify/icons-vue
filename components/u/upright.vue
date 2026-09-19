<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rm-s7t9sf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1023};
const content = `<path class="rm-s7t9sf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:upright" /></template>
