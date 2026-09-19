<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4ji5rb1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v4ji5rb1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:sagittarius" /></template>
