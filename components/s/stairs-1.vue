<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nn_65vfzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="nn_65vfzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:stairs-1" /></template>
