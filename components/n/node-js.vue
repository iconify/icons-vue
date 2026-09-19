<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5mk84iud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h5mk84iud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:node-js" /></template>
