<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9kxh0b9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c9kxh0b9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:volcano-solid" /></template>
