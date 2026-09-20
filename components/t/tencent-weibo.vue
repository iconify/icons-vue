<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nyl66ccho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nyl66ccho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:tencent-weibo" /></template>
