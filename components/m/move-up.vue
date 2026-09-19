<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yu__fdcln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yu__fdcln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:move-up" /></template>
