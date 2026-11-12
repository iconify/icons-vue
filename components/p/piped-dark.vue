<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/le3-1wb0z.css';
import '../../css/k/kmpx0bclz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="le3-1wb0z"/><path class="kmpx0bclz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:piped-dark" /></template>
