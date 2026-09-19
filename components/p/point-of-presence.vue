<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cztp4ub5c.css';
import '../../css/x/xn7w50bnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cztp4ub5c"/><path class="xn7w50bnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:point-of-presence" /></template>
