<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9c833b5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="j9c833b5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:passport-globe-remix" /></template>
