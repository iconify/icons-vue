<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ig2ceckis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ig2ceckis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:play" /></template>
