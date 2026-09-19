<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8_pid-oz.css';
import '../../css/r/rj-fah6et.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c8_pid-oz"/><path class="rj-fah6et"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:strikethrough" /></template>
