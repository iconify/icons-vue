<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1lly_myo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s1lly_myo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:note" /></template>
