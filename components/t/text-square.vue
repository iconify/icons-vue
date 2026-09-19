<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8_pid-oz.css';
import '../../css/c/cy3n3cb9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c8_pid-oz"/><path class="cy3n3cb9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:text-square" /></template>
