<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/feogx6j2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="feogx6j2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:torsher-dark" /></template>
