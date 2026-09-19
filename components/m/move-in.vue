<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c83n9-b_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c83n9-b_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:move-in" /></template>
