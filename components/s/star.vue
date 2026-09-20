<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wghvmdyiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wghvmdyiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:star" /></template>
