<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a27p9svzp.css';
import '../../css/u/u-dqumrtl.css';
import '../../css/k/kzia-bcxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a27p9svzp"/><path class="u-dqumrtl"/><path class="kzia-bcxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:study-read" /></template>
