<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpuhle7eo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cpuhle7eo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:toilet-paper-roll" /></template>
