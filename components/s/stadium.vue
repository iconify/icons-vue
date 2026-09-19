<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2-jwxbjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":704,"height":960};
const content = `<path class="i2-jwxbjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:stadium" /></template>
