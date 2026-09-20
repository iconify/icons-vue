<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kq81fbbqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="kq81fbbqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:nature-flower" /></template>
