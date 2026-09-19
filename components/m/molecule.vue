<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1bwu8bhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="q1bwu8bhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:molecule" /></template>
