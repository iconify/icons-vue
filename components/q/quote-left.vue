<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zf4ud-_ib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zf4ud-_ib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:quote-left" /></template>
