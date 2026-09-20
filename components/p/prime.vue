<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4ihiqo8l.css';
import '../../css/f/fbuv3ib1d.css';
import '../../css/i/i81jb4lpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4ihiqo8l"/><path class="fbuv3ib1d"/><path class="i81jb4lpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:prime" /></template>
