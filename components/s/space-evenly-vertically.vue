<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcl66-bbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vcl66-bbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:space-evenly-vertically" /></template>
