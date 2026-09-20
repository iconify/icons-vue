<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o12_t8byf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o12_t8byf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:minimize-16" /></template>
