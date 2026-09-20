<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2d--yqkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":10,"height":16};
const content = `<path class="u2d--yqkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:repo-forked" /></template>
