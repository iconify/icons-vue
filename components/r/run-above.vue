<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rm48pi--i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rm48pi--i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:run-above" /></template>
