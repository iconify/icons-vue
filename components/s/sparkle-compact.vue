<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4y5kochc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="n4y5kochc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:sparkle-compact" /></template>
