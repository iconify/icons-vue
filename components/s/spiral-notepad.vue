<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3a2aacyc.css';
import '../../css/y/yv8fuzbct.css';
import '../../css/y/yto5y8bbe.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/y/yws1qebfx.css';
import '../../css/r/rp169lb8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="o3a2aacyc"/><path class="yv8fuzbct"/><path class="yto5y8bbe"/><g class="ij2x_72vy"><path class="yws1qebfx"/><path class="rp169lb8c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:spiral-notepad" /></template>
