<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/ms5q2qboz.css';
import '../../css/x/xfac6-bsq.css';
import '../../css/r/rpnamey_h.css';
import '../../css/r/r1qz4mb6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="ms5q2qboz"/><path class="xfac6-bsq"/><path class="rpnamey_h"/><path class="r1qz4mb6j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:red-paper-lantern" /></template>
