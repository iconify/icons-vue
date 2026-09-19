<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vic4fznwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="vic4fznwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:temperature-high" /></template>
