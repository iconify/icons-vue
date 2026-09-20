<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eio6mwq-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="eio6mwq-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:sad-face-with-tear-in-circle-outline" /></template>
