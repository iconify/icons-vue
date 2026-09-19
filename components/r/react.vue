<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgxn76bkp.css';
import '../../css/g/gf2qt1pqt.css';
import '../../css/a/a71-bmb9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<g class="wgxn76bkp"><circle class="gf2qt1pqt"/><path class="a71-bmb9e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:react" /></template>
