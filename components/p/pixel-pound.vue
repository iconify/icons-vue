<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hny70vbls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hny70vbls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-pound" /></template>
