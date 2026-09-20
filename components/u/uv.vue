<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyh13cczf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pyh13cczf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:uv" /></template>
