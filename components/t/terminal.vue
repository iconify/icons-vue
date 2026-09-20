<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q28-3kbsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="q28-3kbsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:terminal" /></template>
