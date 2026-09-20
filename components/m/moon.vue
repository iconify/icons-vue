<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-9vnkbuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="g-9vnkbuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:moon" /></template>
