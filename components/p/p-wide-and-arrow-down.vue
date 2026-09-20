<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8q7uxbee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="z8q7uxbee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:p-wide-and-arrow-down" /></template>
