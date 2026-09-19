<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0q9ccqak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="f0q9ccqak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:surround-with" /></template>
