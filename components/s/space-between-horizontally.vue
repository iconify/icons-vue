<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2ayqabna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="k2ayqabna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:space-between-horizontally" /></template>
