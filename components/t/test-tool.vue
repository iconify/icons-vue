<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8p62x6vn.css';
import '../../css/s/stbfr1b_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k8p62x6vn"/><path class="stbfr1b_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:test-tool" /></template>
