<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-9_xii4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="s-9_xii4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:tea-bag" /></template>
