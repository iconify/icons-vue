<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/levtbqbbg.css';
import '../../css/c/c_o0h-edl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="levtbqbbg"/><path class="c_o0h-edl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:reverse-button" /></template>
