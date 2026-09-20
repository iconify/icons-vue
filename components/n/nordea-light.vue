<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o--qnccve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1515,"height":1477};
const content = `<path class="o--qnccve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:nordea-light" /></template>
