<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xd9pjzbag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xd9pjzbag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:wide-e-with-arrow-right" /></template>
