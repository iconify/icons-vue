<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1wi_jbro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j1wi_jbro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:pencil-16" /></template>
