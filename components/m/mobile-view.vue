<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tiv92mbuz.css';
import '../../css/f/fu98lubud.css';
import '../../css/o/o32ixwgun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="tiv92mbuz"/><path class="fu98lubud"/><path class="o32ixwgun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:mobile-view" /></template>
