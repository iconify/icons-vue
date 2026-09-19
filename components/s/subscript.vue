<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qv323eboo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qv323eboo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:subscript" /></template>
