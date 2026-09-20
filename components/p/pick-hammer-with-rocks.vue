<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gettf3w-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gettf3w-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pick-hammer-with-rocks" /></template>
