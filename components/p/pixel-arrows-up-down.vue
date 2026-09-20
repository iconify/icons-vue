<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1hvo3b0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="p1hvo3b0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-arrows-up-down" /></template>
