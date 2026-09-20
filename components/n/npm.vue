<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/juvuk6mdh.css';
import '../../css/f/fi4s-dblz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2500,"height":2500};
const content = `<path class="juvuk6mdh"/><path class="fi4s-dblz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:npm" /></template>
