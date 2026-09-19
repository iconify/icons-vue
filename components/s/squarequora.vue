<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5zy_5-qj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="f5zy_5-qj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:squarequora" /></template>
