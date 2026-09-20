<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wycvh4b1h.css';
import '../../css/h/hnh9ojyty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="wycvh4b1h"/><path class="hnh9ojyty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:white-medium-small-square" /></template>
