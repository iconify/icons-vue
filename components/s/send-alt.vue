<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syv80hb5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="syv80hb5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:send-alt" /></template>
