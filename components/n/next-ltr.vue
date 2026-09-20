<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfq4g4h5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zfq4g4h5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:next-ltr" /></template>
