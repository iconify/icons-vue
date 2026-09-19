<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4ostgxng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1027};
const content = `<path class="u4ostgxng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:pigpeny" /></template>
