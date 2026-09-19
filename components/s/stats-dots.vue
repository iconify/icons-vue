<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eghdr7tiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="eghdr7tiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:stats-dots" /></template>
