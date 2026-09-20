<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e49kknb2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="e49kknb2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:round-rock" /></template>
