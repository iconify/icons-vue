<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/px_xisjvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="px_xisjvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:workspace" /></template>
