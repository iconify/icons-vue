<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yn-nsjbqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yn-nsjbqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pango-dark" /></template>
