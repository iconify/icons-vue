<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xez50c7he.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xez50c7he"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:stop" /></template>
