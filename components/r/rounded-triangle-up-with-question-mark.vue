<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh609ibnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rh609ibnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:rounded-triangle-up-with-question-mark" /></template>
