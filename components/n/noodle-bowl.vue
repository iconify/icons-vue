<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytc-hrbpf.css';
import '../../css/x/xtnb74b1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ytc-hrbpf"/><path class="xtnb74b1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:noodle-bowl" /></template>
