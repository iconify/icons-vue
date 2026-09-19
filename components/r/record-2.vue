<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qr5agrbuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="qr5agrbuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:record-2" /></template>
