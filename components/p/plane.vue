<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb2a1qwds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zb2a1qwds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:plane" /></template>
