<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2bhn2v8h.css';
import '../../css/w/whvapjd8j.css';
import '../../css/o/o_af29byo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u2bhn2v8h"/><path class="whvapjd8j"/><path class="o_af29byo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:satellite-20" /></template>
