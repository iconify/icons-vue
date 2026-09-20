<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8ddtabcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v8ddtabcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:share" /></template>
