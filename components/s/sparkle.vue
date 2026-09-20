<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqlr9bbbp.css';
import '../../css/z/zln5icnwf.css';
import '../../css/m/mfvow-bah.css';
import '../../css/i/iwjrb3bnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="jqlr9bbbp"/><path class="zln5icnwf"/><path class="mfvow-bah"/><path class="iwjrb3bnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:sparkle" /></template>
