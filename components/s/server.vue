<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1e0vbssl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="j1e0vbssl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:server" /></template>
