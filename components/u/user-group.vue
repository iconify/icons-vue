<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jz9dst_jq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1792};
const content = `<path class="jz9dst_jq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:user-group" /></template>
