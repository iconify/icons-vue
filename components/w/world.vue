<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ld-l217ao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ld-l217ao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:world" /></template>
