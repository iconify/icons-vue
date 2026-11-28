<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/roxidabpe.css';
import '../../css/n/nckoucbbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="roxidabpe secondary"/><path class="nckoucbbw primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:square-round-corner-duo" /></template>
