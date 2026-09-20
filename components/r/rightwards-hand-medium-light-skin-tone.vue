<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jaot0vf8m.css';
import '../../css/n/nw_fw7zya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="jaot0vf8m"/><path class="nw_fw7zya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:rightwards-hand-medium-light-skin-tone" /></template>
