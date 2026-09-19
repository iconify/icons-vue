<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4juzibaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="s4juzibaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:window-close" /></template>
