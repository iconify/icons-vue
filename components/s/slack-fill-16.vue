<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzfpc1bor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xzfpc1bor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:slack-fill-16" /></template>
