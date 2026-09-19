<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj2xsotgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mj2xsotgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:server" /></template>
