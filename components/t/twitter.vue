<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2h_x22up.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a2h_x22up"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:twitter" /></template>
