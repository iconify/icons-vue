<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znpy9zbqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="znpy9zbqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:square" /></template>
