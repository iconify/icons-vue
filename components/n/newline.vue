<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kwx5fiwjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kwx5fiwjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:newline" /></template>
