<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohh30p-3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="ohh30p-3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:panel-bottom" /></template>
