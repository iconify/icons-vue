<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8kqwv81x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c8kqwv81x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:rectangle-small" /></template>
