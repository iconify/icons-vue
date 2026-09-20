<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfuanbccs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":800,"height":405};
const content = `<path class="tfuanbccs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:xstate-light" /></template>
