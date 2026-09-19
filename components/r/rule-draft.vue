<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3lmd4bmk.css';
import '../../css/f/fvmh2ibcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f3lmd4bmk"/><path class="fvmh2ibcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:rule-draft" /></template>
