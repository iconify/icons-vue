<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q99b8eiec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="q99b8eiec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:padding" /></template>
