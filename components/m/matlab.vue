<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zziiasbpq.css';
import '../../css/z/z176l2i0d.css';
import '../../css/u/ubkr3mbhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":720,"height":720};
const content = `<path class="zziiasbpq"/><path class="z176l2i0d"/><path class="ubkr3mbhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:matlab" /></template>
