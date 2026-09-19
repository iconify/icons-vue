<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0c2y_bmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="q0c2y_bmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:skull" /></template>
