<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g95454bvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g95454bvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:ruby-16" /></template>
