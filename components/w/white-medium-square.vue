<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i43r0eb1n.css';
import '../../css/y/y3rmrqmdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="i43r0eb1n"/><path class="y3rmrqmdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:white-medium-square" /></template>
