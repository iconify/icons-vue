<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8ttspegr.css';
import '../../css/v/v2yh4c2xt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="u8ttspegr"/><path class="v2yh4c2xt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:raising-hands" /></template>
