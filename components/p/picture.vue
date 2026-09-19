<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l939jq-il.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="l939jq-il"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:picture" /></template>
