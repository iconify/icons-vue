<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yiy-tl0rx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yiy-tl0rx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:three-dots-vertical" /></template>
