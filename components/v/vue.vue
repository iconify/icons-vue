<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z792yubyf.css';
import '../../css/g/gpbvbidrc.css';
import '../../css/j/jjet8kudg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":221};
const content = `<path class="z792yubyf"/><path class="gpbvbidrc"/><path class="jjet8kudg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:vue" /></template>
