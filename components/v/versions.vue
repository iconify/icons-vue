<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnnzszuru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":16};
const content = `<path class="cnnzszuru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:versions" /></template>
