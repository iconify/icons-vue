<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akufad7xf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="akufad7xf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:thick-arrow-right" /></template>
