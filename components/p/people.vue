<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfhx01_3w.css';
import '../../css/l/lwt2_3bbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":16};
const content = `<path class="yfhx01_3w"/><path class="lwt2_3bbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:people" /></template>
