<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxs02k2xl.css';
import '../../css/c/c681w5y_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qxs02k2xl"/><path class="c681w5y_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:wifi-not-secure" /></template>
