<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fw9acm4lh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":16};
const content = `<path class="fw9acm4lh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:unfold" /></template>
