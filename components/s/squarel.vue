<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/on18ujy8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="on18ujy8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:squarel" /></template>
