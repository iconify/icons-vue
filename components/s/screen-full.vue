<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9z9ypwvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":16};
const content = `<path class="c9z9ypwvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:screen-full" /></template>
