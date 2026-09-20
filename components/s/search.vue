<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yynh3uk2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yynh3uk2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nimbus:search" /></template>
