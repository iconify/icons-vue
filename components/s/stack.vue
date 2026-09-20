<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfx6ry1aw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jfx6ry1aw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:stack" /></template>
