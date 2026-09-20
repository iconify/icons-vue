<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fa1_sbb_c.css';
import '../../css/c/c4dmikbsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="fa1_sbb_c"/><path class="c4dmikbsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:white-vertical-ellipse" /></template>
