<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9k58leho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i9k58leho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:shoelace" /></template>
