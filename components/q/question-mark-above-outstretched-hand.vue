<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgqu7acml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tgqu7acml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:question-mark-above-outstretched-hand" /></template>
