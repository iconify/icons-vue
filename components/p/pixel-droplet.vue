<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ra5q_ibby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ra5q_ibby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-droplet" /></template>
