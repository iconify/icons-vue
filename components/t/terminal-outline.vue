<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njic2363g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="njic2363g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:terminal-outline" /></template>
