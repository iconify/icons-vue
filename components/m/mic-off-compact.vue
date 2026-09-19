<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3ientf3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="q3ientf3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:mic-off-compact" /></template>
