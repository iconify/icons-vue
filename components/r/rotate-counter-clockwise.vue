<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/diykwy11w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="diykwy11w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:rotate-counter-clockwise" /></template>
