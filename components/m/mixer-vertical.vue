<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjd0kis-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rjd0kis-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:mixer-vertical" /></template>
