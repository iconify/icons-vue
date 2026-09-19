<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1de7ob0p.css';
import '../../css/f/fi8p1vbsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i1de7ob0p"/><path class="fi8p1vbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:restaurant" /></template>
