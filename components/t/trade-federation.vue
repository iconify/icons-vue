<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3k_xj7cj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="r3k_xj7cj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:trade-federation" /></template>
