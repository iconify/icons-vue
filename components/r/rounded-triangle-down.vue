<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-xkcdijr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="i-xkcdijr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:rounded-triangle-down" /></template>
