<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wix2zkbpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="wix2zkbpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:stopwatch" /></template>
