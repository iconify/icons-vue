<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g2dxccp7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="g2dxccp7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:terminal-cli-stroke-12" /></template>
