<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4723tbqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="z4723tbqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:minimize" /></template>
