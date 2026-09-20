<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4-z48bjf.css';
import '../../css/h/hua-a9bjv.css';
import '../../css/n/nr0sg1b4q.css';
import '../../css/y/y85-cbbqp.css';
import '../../css/c/cd7p0qbfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="k4-z48bjf"/><path class="hua-a9bjv"/><path class="nr0sg1b4q"/><path class="y85-cbbqp"/><path class="cd7p0qbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:warning-strip" /></template>
