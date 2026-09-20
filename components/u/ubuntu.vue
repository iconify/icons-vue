<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfvl_quvy.css';
import '../../css/x/xwnqe-beb.css';
import '../../css/u/u4z7rnb1i.css';
import '../../css/c/clgcxl7va.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="xfvl_quvy"/><path clip-rule="evenodd" class="xwnqe-beb"/><path class="u4z7rnb1i"/><path class="clgcxl7va"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:ubuntu" /></template>
