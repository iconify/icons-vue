<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv7zpptfp.css';
import '../../css/x/xnpc5acoh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gv7zpptfp"/><path class="xnpc5acoh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:nx" /></template>
