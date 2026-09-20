<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j13sb7b-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1515,"height":1477};
const content = `<path class="j13sb7b-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:nordea" /></template>
