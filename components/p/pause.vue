<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0f1rtbgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="c0f1rtbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:pause" /></template>
