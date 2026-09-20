<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8ckk_crr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="r8ckk_crr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:space-between-vertically" /></template>
