<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f65bd6b3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f65bd6b3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:table" /></template>
