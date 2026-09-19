<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kz4nh0bqh.css';
import '../../css/l/ll2dvhb-d.css';
import '../../css/n/n8o1_4bxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kz4nh0bqh"/><path class="ll2dvhb-d"/><path class="n8o1_4bxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:woman-frowning" /></template>
