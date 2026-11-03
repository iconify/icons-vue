<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3ti3obmt.css';
import '../../css/j/jlpxzebyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="k3ti3obmt"/><path class="jlpxzebyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:wavy-dash" /></template>
