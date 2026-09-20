<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iri9dpb6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iri9dpb6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:stopwatch" /></template>
