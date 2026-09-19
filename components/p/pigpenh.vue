<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ik25i8w8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="ik25i8w8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:pigpenh" /></template>
