<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbkalab5n.css';
import '../../css/j/jut-sxzup.css';
import '../../css/y/yf6vu0_hw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="zbkalab5n"/><path class="jut-sxzup"/><path class="yf6vu0_hw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:top-hat" /></template>
