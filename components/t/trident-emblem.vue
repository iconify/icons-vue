<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqqcd7bya.css';
import '../../css/u/ul_bi8ihr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="hqqcd7bya"/><path class="ul_bi8ihr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:trident-emblem" /></template>
