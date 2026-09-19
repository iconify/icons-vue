<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxr4-wf7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="fxr4-wf7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:next" /></template>
