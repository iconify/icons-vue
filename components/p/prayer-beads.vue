<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zhpcxnv_f.css';
import '../../css/u/u3zv7hbgk.css';
import '../../css/s/sldujvbwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="zhpcxnv_f"/><path class="u3zv7hbgk"/><path class="sldujvbwa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:prayer-beads" /></template>
