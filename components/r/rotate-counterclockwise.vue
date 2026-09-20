<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lg_wztg3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="lg_wztg3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:rotate-counterclockwise" /></template>
