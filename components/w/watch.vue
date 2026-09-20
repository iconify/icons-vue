<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owh6n4siz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":16};
const content = `<path class="owh6n4siz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:watch" /></template>
