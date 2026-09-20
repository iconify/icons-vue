<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddq_2tbpa.css';
import '../../css/u/u9_0cx3wu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="ddq_2tbpa"/><path class="u9_0cx3wu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:soon-arrow" /></template>
