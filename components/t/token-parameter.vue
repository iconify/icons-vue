<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6oxynubr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k6oxynubr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:token-parameter" /></template>
