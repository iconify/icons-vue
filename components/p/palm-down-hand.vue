<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ay78_wwsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ay78_wwsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:palm-down-hand" /></template>
