<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ls3x4fbrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ls3x4fbrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:newspaper" /></template>
