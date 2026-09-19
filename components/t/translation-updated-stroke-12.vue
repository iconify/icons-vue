<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9b1e13eh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="c9b1e13eh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:translation-updated-stroke-12" /></template>
