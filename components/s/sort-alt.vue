<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sg1-embqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sg1-embqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:sort-alt" /></template>
