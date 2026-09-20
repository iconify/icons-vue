<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrfh4bqnd.css';
import '../../css/f/fpe9bqb4y.css';
import '../../css/q/qcqglrpgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<rect class="wrfh4bqnd"/><path class="fpe9bqb4y"/><circle class="qcqglrpgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:nubjs" /></template>
