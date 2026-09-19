<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-go91ypk.css';
import '../../css/m/mkwx26bok.css';
import '../../css/f/fv05gfbud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n-go91ypk"/><path class="mkwx26bok"/><path class="fv05gfbud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:webhook" /></template>
