<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tj8pek22w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="tj8pek22w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:sailboat" /></template>
