<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbfmdkbwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bbfmdkbwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:sketch-logo" /></template>
