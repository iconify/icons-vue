<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3q134bfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="y3q134bfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:size" /></template>
