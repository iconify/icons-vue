<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-s4jxb4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="i-s4jxb4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:save" /></template>
