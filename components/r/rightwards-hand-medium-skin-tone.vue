<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zl71cr7wd.css';
import '../../css/n/nw_fw7zya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="zl71cr7wd"/><path class="nw_fw7zya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:rightwards-hand-medium-skin-tone" /></template>
