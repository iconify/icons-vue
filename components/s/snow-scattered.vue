<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ys42lxb9r.css';
import '../../css/k/ky_i-dbux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ys42lxb9r"/><path class="ky_i-dbux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:snow-scattered" /></template>
