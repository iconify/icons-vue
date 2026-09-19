<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng-8hw7il.css';
import '../../css/p/p38-woblf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ng-8hw7il"/><path class="p38-woblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:rule-locked" /></template>
