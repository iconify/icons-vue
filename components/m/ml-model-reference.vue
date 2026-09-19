<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtnvolzvt.css';
import '../../css/x/xd2sz9b9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mtnvolzvt"/><path class="xd2sz9b9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ml-model-reference" /></template>
