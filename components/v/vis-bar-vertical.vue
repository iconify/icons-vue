<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhrp6sb2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qhrp6sb2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:vis-bar-vertical" /></template>
