<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wk2c95-jo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":768};
const content = `<path class="wk2c95-jo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:mayanpyramid" /></template>
