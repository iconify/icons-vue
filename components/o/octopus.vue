<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axae4tbjw.css';
import '../../css/c/cmgm03bvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="axae4tbjw"/><path class="cmgm03bvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:octopus" /></template>
