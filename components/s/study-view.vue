<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhkw86bin.css';
import '../../css/x/x8cmsqbjt.css';
import '../../css/t/tx7rwubgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yhkw86bin"/><path class="x8cmsqbjt"/><path class="tx7rwubgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:study-view" /></template>
