<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-29oacxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j-29oacxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:spell-check" /></template>
