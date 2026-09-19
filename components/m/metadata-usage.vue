<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/moxgezhzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="moxgezhzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:metadata-usage" /></template>
