<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jho-fuw1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jho-fuw1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:save" /></template>
