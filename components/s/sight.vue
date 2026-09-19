<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qx_1zebpd.css';
import '../../css/i/i2ck-cb3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qx_1zebpd"/><path class="i2ck-cb3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:sight" /></template>
