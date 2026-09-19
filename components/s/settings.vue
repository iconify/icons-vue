<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/joqi56b4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":416,"height":432};
const content = `<path class="joqi56b4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:settings" /></template>
