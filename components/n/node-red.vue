<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-eh3wbpz.css';
import '../../css/j/j-38zcbgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f-eh3wbpz"/><path class="j-38zcbgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:node-red" /></template>
