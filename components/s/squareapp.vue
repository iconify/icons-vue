<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt9y4u0px.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="jt9y4u0px"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:squareapp" /></template>
