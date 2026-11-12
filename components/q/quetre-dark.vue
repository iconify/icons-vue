<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3pbf6byq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m3pbf6byq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:quetre-dark" /></template>
