<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gc0qmpbsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gc0qmpbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:triangle-left" /></template>
