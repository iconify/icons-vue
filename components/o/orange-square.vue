<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bx2r13bpi.css';
import '../../css/q/qy2vo7bko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="bx2r13bpi"/><path class="qy2vo7bko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:orange-square" /></template>
