<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ways3sbhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1025};
const content = `<path class="ways3sbhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:twofingerswipeup" /></template>
