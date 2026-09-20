<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b11hx3r3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="b11hx3r3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:steps-number-remix" /></template>
