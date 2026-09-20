<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ityqu6bxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="ityqu6bxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:refresh-alt" /></template>
