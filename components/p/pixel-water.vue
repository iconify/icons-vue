<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uq21gubaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="uq21gubaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-water" /></template>
