<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpcu2565j.css';
import '../../css/r/rs94qeblu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cpcu2565j"/><path class="rs94qeblu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:stickies" /></template>
