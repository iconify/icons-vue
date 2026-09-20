<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d99mpp4pu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="d99mpp4pu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:plus-circled" /></template>
