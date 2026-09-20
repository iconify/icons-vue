<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmna-ibde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="wmna-ibde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:scanner" /></template>
