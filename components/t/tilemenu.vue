<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5mwqbc4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":666,"height":680};
const content = `<path class="j5mwqbc4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:tilemenu" /></template>
