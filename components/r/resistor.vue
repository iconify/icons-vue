<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtlufubel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":614};
const content = `<path class="qtlufubel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:resistor" /></template>
