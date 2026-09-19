<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcay24bda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jcay24bda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:recording-filled-alt" /></template>
