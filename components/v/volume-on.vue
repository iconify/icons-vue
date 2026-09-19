<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oewbiur4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2016,"height":1728};
const content = `<path class="oewbiur4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:volume-on" /></template>
