<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt-9xdinh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="jt-9xdinh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:soup" /></template>
