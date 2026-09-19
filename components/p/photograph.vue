<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtksr2b6j.css';
import '../../css/j/j4-0chb9k.css';
import '../../css/r/ratngrhrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":27,"height":24};
const content = `<path class="xtksr2b6j"/><path class="j4-0chb9k"/><path class="ratngrhrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:photograph" /></template>
