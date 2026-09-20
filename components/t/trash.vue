<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqn9hibsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xqn9hibsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:trash" /></template>
