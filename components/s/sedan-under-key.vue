<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6ivcfb-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="z6ivcfb-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:sedan-under-key" /></template>
