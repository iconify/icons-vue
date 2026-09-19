<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/c1yl4eviw.css';
import '../../css/m/md286fbip.css';
import '../../css/m/m7qoyzbmt.css';
import '../../css/w/w5l_6vebe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle class="c1yl4eviw"/><g class="md286fbip"><path class="m7qoyzbmt"/><path class="w5l_6vebe"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency-color:payx" /></template>
