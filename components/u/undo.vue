<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4v87jbma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="q4v87jbma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:undo" /></template>
