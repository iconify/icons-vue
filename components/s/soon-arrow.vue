<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddq_2tbpa.css';
import '../../css/a/avm-knshb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="ddq_2tbpa"/><path class="avm-knshb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:soon-arrow" /></template>
