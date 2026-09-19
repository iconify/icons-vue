<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1b95sj3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c1b95sj3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:parachute-box" /></template>
