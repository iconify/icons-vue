<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wx00fkbkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wx00fkbkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:plus-16" /></template>
