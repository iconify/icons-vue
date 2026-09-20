<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2ukffbfm.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/o/ope5ptb9j.css';
import '../../css/d/d9dngzb9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="e2ukffbfm"/><g class="ij2x_72vy"><circle class="ope5ptb9j"/><path class="d9dngzb9u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:sun" /></template>
