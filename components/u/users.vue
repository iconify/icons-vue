<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sf67_cc1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="sf67_cc1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:users" /></template>
