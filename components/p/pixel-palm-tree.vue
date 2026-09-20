<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gw3nfyb4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gw3nfyb4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-palm-tree" /></template>
