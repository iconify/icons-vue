<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyj7ucbsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cyj7ucbsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:tunnel" /></template>
