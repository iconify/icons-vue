<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zg9u1fbeg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="zg9u1fbeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:qrcode" /></template>
