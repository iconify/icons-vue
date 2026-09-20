<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsejinj5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nsejinj5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:volume-down-ltr" /></template>
