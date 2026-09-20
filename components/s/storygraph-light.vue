<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi470-s6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oi470-s6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:storygraph-light" /></template>
