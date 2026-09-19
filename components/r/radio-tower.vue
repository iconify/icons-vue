<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aqbrvsh0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="aqbrvsh0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:radio-tower" /></template>
