<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqar3gbvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="aqar3gbvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:multiline-stroke-12" /></template>
