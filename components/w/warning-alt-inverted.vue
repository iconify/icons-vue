<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt8z3m2uo.css';
import '../../css/r/r6ujjtbfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jt8z3m2uo"/><path class="r6ujjtbfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:warning-alt-inverted" /></template>
