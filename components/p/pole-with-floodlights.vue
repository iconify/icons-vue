<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nu9nlz-2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nu9nlz-2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pole-with-floodlights" /></template>
