<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gopuiz2dq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gopuiz2dq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-walking-holding-railing" /></template>
