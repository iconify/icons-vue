<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1gv4pp8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i1gv4pp8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:zerobyte" /></template>
