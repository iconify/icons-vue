<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uu77ymb3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uu77ymb3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:media-skip-forward" /></template>
