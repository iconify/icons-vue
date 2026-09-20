<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z22cmu4ni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="z22cmu4ni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:new-york" /></template>
