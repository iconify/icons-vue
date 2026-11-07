<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt4erfbgl.css';
import '../../css/k/kr5538bfj.css';
import '../../css/i/inp7-fbxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gt4erfbgl"/><path class="kr5538bfj"/><path class="inp7-fbxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-sort-vertical-bold-duotone" /></template>
