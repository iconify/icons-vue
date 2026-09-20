<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mglbfiean.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mglbfiean"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:view-none" /></template>
