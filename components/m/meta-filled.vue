<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhsimbvhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="uhsimbvhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:meta-filled" /></template>
