<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cmlrd2dzs.css';
import '../../css/p/pcxg8ubdq.css';
import '../../css/i/ig17hdb9u.css';
import '../../css/y/ym70or71v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="cmlrd2dzs"/><path class="pcxg8ubdq"/><path class="ig17hdb9u"/><path class="ym70or71v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:pie" /></template>
