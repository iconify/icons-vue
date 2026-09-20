<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq0r3bb7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="cq0r3bb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:museum-14" /></template>
