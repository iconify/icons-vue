<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iioj3obui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="iioj3obui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:people" /></template>
