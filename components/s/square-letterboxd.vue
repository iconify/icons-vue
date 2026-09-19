<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajbve8uyk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ajbve8uyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:square-letterboxd" /></template>
