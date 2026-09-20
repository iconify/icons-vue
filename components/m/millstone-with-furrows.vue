<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dr-49bb3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dr-49bb3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:millstone-with-furrows" /></template>
