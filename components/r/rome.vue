<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jngg2rbis.css';
import '../../css/w/w0onahbsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jngg2rbis"/><path class="w0onahbsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:rome" /></template>
