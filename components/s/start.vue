<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2y5ycc9l.css';
import '../../css/u/ujx7g2v4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":16};
const content = `<path class="y2y5ycc9l"/><path class="ujx7g2v4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:start" /></template>
