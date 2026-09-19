<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nj3eh0r6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="nj3eh0r6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:next" /></template>
