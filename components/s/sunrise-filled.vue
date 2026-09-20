<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dn8bx52jh.css';
import '../../css/h/hidu0kbkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dn8bx52jh"/><path class="hidu0kbkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:sunrise-filled" /></template>
