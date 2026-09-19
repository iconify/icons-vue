<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/by4kbj5ev.css';
import '../../css/h/hhg6y4bgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="by4kbj5ev"/><path class="hhg6y4bgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:sqlite-wordmark" /></template>
