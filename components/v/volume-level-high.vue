<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6kjdab9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="j6kjdab9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:volume-level-high" /></template>
