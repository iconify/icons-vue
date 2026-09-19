<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vuj4p-a8q.css';
import '../../css/j/j8hs3szgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vuj4p-a8q"/><path class="j8hs3szgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:tablet" /></template>
