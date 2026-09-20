<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_0r4ob-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c_0r4ob-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:nature-sun" /></template>
