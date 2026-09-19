<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmxe8fbjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cmxe8fbjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:page-break" /></template>
