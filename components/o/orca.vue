<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr24jkwsh.css';
import '../../css/a/ao18k45ue.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/d/ducf-wbyw.css';
import '../../css/n/nhrj7sblw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="jr24jkwsh"/><path class="ao18k45ue"/><g class="ij2x_72vy"><path class="ducf-wbyw"/><path class="nhrj7sblw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:orca" /></template>
