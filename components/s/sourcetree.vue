<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eg3ny2g5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="eg3ny2g5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:sourcetree" /></template>
