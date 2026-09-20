<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvhs7gbxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mvhs7gbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:mask-on" /></template>
