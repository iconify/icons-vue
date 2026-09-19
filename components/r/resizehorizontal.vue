<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8y7v2bwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":641};
const content = `<path class="l8y7v2bwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:resizehorizontal" /></template>
