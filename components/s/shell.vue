<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cy-1rpbyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":833};
const content = `<path class="cy-1rpbyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:shell" /></template>
