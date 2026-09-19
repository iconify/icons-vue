<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrnwts-5v.css';
import '../../css/t/t0dn9ubiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<g transform="translate(-173.29 -80.936)scale(3.77953)"><rect class="yrnwts-5v"/><path class="t0dn9ubiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:yunohost" /></template>
