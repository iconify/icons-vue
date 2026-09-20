<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrjvicbzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="jrjvicbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:train" /></template>
