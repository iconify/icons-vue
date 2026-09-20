<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2oc4mbya.css';
import '../../css/y/ye2ymf1gu.css';
import '../../css/t/tu7ylzb3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f2oc4mbya"/><path class="ye2ymf1gu"/><path class="tu7ylzb3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:siyuan" /></template>
