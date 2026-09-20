<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhlo1mbfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jhlo1mbfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:picture" /></template>
