<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/m6d6doeil.css';
import '../../css/z/z1z870b5e.css';
import '../../css/a/ay85fxbvo.css';
import '../../css/i/in6k146eo.css';
import '../../css/a/au8b_6b3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="m6d6doeil"/><path class="z1z870b5e"/><path class="ay85fxbvo"/><path class="in6k146eo"/><path class="au8b_6b3q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:petri-dish" /></template>
