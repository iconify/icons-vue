<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqr2b_b3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sqr2b_b3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tracktor-dark" /></template>
