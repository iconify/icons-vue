<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5vj-ib1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l5vj-ib1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:orca-slicer-light" /></template>
