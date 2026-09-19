<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2ljqbzto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2000,"height":2000};
const content = `<path class="r2ljqbzto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:space-tool" /></template>
