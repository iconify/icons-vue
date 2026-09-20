<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_0enm4cu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r_0enm4cu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:other-arrows-move" /></template>
