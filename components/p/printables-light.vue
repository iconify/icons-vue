<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpl6xib5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fpl6xib5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:printables-light" /></template>
