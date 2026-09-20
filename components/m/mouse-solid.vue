<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unerd9b0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="unerd9b0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:mouse-solid" /></template>
